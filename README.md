# Lee Tae Soo | Cloud Engineer

```
$ whoami
안정적인 서비스를 위한 인프라를 설계하고 운영하는 클라우드 엔지니어입니다.
```

## What I Pursue

```
1. 장애 없는 서비스 - 안정성과 가용성을 최우선으로
2. 자동화된 운영 - 반복 작업은 코드로, 사람은 창의적인 일에
3. 보안이 기본인 설계 - 사후 대응이 아닌 사전 예방
```

---

## Projects

### [MovieSir](https://github.com/Movigation) - AI 영화 추천 B2B API

> LightGCN + SBERT 하이브리드 추천 알고리즘 기반 B2B API 서비스

| 링크                                      | 설명         |
| ----------------------------------------- | ------------ |
| [Demo](https://demo.moviesir.cloud)       | 서비스 체험  |
| [Console](https://console.moviesir.cloud) | B2B API 콘솔 |

**담당:** 인프라 설계, CI/CD 구축, 서버 보안

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

---

### [읽어드림](https://github.com/leelaeloo/Senior-OCR-Project) - 어르신들을 위한 문서 읽어주기 앱

> 시니어 친화 OCR PWA

**특징:** OCR + TTS + PWA

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

---

### Infra Practice

| 프로젝트                                                                    | 설명             | 학습 내용                            |
| --------------------------------------------------------------------------- | ---------------- | ------------------------------------ |
| [Docker-Load-Balancing](https://github.com/leelaeloo/Docker-Load-Balancing) | Nginx 로드밸런싱 | Docker Compose, Round Robin          |
| [K8s-Windows-WSL2](https://github.com/leelaeloo/K8s-Windows-WSL2)           | CKA 준비         | Deployment, Service, Troubleshooting |

---

## What I Did (MovieSir)

### Security Hardening

```bash
# SSH 브루트포스 공격 1,843건 탐지 및 대응
$ sudo lastb | wc -l
1843

# 대응 결과
- 169개 IP 자동 차단 (fail2ban)
- SSH 포트 변경 + Bastion Host 구성
- GPU Server 공격 0건 달성
```

### CI/CD Pipeline

```
GitHub Actions (dev/main branch push)
├── frontend/** → App Server 배포
├── backend/** → App Server 배포 (Docker)
└── ai/** → GPU Server 배포 (Bastion 경유)
```

---

## Tech Stack

**Infra & Cloud**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Database**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Security**

![fail2ban](https://img.shields.io/badge/fail2ban-CC0000?style=flat-square&logo=linux&logoColor=white)
![UFW](https://img.shields.io/badge/UFW-E95420?style=flat-square&logo=ubuntu&logoColor=white)

---

## Velog

클라우드 인프라 구축기 시리즈

| #   | 제목                                                                                                                                                                                                                           |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1   | [KakaoCloud 2-Tier 아키텍처 설계](https://velog.io/@leelaeloo/%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C-%EC%9D%B8%ED%94%84%EB%9D%BC-%EA%B5%AC%EC%B6%95%EA%B8%B0-1)                                                                  |
| 2   | [GitHub Actions로 CI/CD 구축하기](https://velog.io/@leelaeloo/%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C-%EC%9D%B8%ED%94%84%EB%9D%BC-%EA%B5%AC%EC%B6%95%EA%B8%B0-2/클라우드-인프라-구축기-GitHub-Actions로-CICD-파이프라인-구축하기) |
| 3   | [SSH 브루트포스 1,843건 대응기](https://velog.io/@leelaeloo/클라우드-인프라-구축기-SSH-브루트포스-1843건-대응기)                                                                                                               |

---

## Currently Learning

```
[x] Docker & Docker Compose
[x] GitHub Actions CI/CD
[ ] Kubernetes (CKA 준비 중)
[ ] Terraform
[ ] AWS Solutions Architect
```

---

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=leelaeloo&show_icons=true&theme=dark&hide_border=true)

---

## Contact

[![Velog](https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=velog&logoColor=white)](https://velog.io/@leelaeloo/)

```
Email: taesoolee9923@gmail.com
```
