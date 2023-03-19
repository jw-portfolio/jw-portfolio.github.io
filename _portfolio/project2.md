---
title: IDT-Manager
subtitle: 쿠버네티스를 이용한 디지털 트윈 리소스 관리
image: assets/img/portfolio/kubesphere.jpeg
alt: IDT-Manager

caption:
  title: IDT-Manager
  subtitle: 쿠버네티스를 이용한 디지털 트윈 리소스 관리
  thumbnail: assets/img/portfolio/kubesphere.jpeg
---

스마트 팩토리에서 디지털 트윈 리소스를 관리하기 위해 Kubesphere라는 클라우드 네이티브 애플리케이션 관리를 위한 분산 운영체제를 도입했습니다.

![그림1](/assets/img/portfolio/k8s_infra.png){: .img-fluid}

**구축 과정:**

1\. AWS 환경에 EKS 쿠버네티스 환경 구축  
2\. Kubesphere 서비스 구축  
3\. EFS 구축 및 필요한 디지털 트윈 리소스 EFS에 저장  
4\. 디지털 트윈 서버를 도커 이미지로 구현 및 DockeHub에 등록  
5\. 배포를 위한 Helm Chrt 생성  
6\. Helm Chart 패키지 Kubesphere에 등록  
7\. Kubesphere에서 마스터 노드에 명령을 내리고 디지털 트윈 서버를 띄울 때 EFS에 저장되어 있는 리소스들을 가져와 자동 배포

**결과:**

Kubesphere 웹 환경에서 배포 클릭만 하면 자동으로 디지털 트윈 서버가 배포가 되고 쿠버네티스 리소스로 관리가 가능한 형태로 띄워짐

**제조 환경에서의 쿠버네티스 도입의 장점**

\- 쿠버네티스 서비스를 적용하여 제조 현장에 올라와 있는 모든 서비스를 격리 시키는 구조로 구성할 수 있으므로 다른 환경에 독립적으로 동작이 가능하다.  
\- 제조 현장에서 과도한 리소스 사용으로 인한 부하를 사전에 방지하고 부하 분배 가능하다.  
\- 제조 현장에서 운용되는 수 많은 서비스들을 일관성 있고 손쉽게 배포가 가능하다

{:.list-inline}

- **Date:** December 2022
- **Skills:** Docker, Kubernetes, Helm
- **Category:** Digital Twin, DevOps
