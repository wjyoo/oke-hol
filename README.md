# CI/CD with OKE(Oracle Container Engine for Kubernetes) Hands-On
 (Oracle Modern Cloud Day 2019의 Tech Hands-on Track)

![](images/header_redwood_3.png)
 
## Introduction
본 핸즈온 문서는 Oracle Developer Cloud Service를 사용하여 간단한 샘플 Application을 Oracle Container Engine for Kubernetes 에 배포하고 CI/CD 기능을 활용해 자동으로 빌드하고 배포하는 과정을 다루고 있습니다. 본 과정을 통해서 기본적인 오라클 Devleloper Cloud의 CI/CD 기능과 Oracle Kubernetes의 기능들을 경험을 해볼 수 있습니다.

## Objectives
* OKE(Oracle Container Engine for Kubernetes) 의 이해
* Developer Cloud Service의 CI/CD 확인

## Required Artifacts
* 인터넷 접속 가능한 PC
* OCI (Oracle Cloud Infrastructure) 계정
* SSH Terminal (windows Putty, macOS Terminal 등)

## 실습을 위한 클라이언트 개발 환경
* 실습 개발 환경 IP : 140.238.18.26
* 사용자명 / Password : Paper로 제공
* 클라우드 접속 계정
> 접속 방법  
> ssh -i id_rsa 사용자명@140.238.18.26

## 시나리오
![](images/sceneall.png)


## Hands-On 순서

1. [Oracle Kubernetes 환경 확인하기](./oke.md)
1. [Developer Cloud Service 에 접속하기](./devcs.md)
1. [Developer Cloud Service 에서 Build 생성하기](./cicd.md)
1. [Application 확인, CI/CD 를 통한 자동화](./app.md)