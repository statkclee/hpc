---
layout: page
title: $100 달러 오픈 슈퍼 컴퓨터
subtitle: 오픈스택
minutes: 10
---

> ### 학습 목표 {.objectives}
>
> * 오픈스택을 소개한다.
> * 오픈스택을 설치한다.

### 오픈스택 아키텍쳐

오픈스택는 수많은 글로벌 기업의 최고의 엔지니어가 이제 제법 시간을 두고 개발을 진행해서 소프트웨어 자체도 매우 복잡해졌다. 하지만, 오픈스택을 개발할 당시 정한 기본적인 아키텍쳐 결정 사항은 변한 것은 없고, [Solinea](http://www.solinea.com/)에서 글리즐리(Grizzly) 버젼[^1]으로 작성된 오픈스택 아키텍쳐를 참고 살펴보는 것이 빠른 시간 내에 핵심적인 내용을 섭렵하는데 도움이 될 것이다. 

[^1]: [Introduction to OpenStack Architecture: Grizzly Edition](http://www.solinea.com/blog/openstack-summit-intro-to-openstack-architecture-grizzly-edition)

> ### 핵심 품질속성 변수 {.callout}
> 
> - Loosely Coupled Architecture (큐, queue) : 확장성(Scalability)
> - API 인터페이스

Solinea에서 발표된 오픈스택 개념 아키텍처를 대쉬보드(Horizon)을 별도로 빼서 핵심 내용만 재구성

<img src="fig/openstack-concept-architecture.png" width="70%" />


### 핵심 구성요소

1. 컴퓨터(Compute): 노바(Nova)
1. 객체저장소(Object Storage): 스위프트(Swift)
1. 이미지관리(Image Management): 글랜스(Glance)
1. 인증관리(Identify Management): 키스톤(Keystone)
1. 인터페이스(Dashboard): 호라이즌(Horizon)
1. 네트워킹(Networking): 뉴트론(Neutron)
1. 블록저장소(Block Storage): 신더(Cinder)
1. 모니터링과 계량기(Monitoring and Metering): 실로미터(Ceilometer) 
1. 오케스트레이션(Orchestration): 히트(Heat) 


### 오픈스택 툴체인(Tool-Chain) 

1. 

