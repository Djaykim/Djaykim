# 김동진 포트폴리오
## Intro
> 안녕하세요! ***"개발자가 개발만 할 수 있는 환경"*** 을   
> 만들고 싶은 13년차 웹개발자 김동진 입니다

## Core Ability
* 다양한 웹 개발 경험(JAVA, C#, php), 오픈소스 기반 기술 검토 및 구축 사례 다수로 최적의 솔루션 제안
* 여러 개발언어의 소스분석이 가능 하여 Legacy를 분석 하고 타 솔루션과 협업 및 개발 운영이 가능
* 형상관리(git), 이슈관리(redmine), 빌드서버(Jenkins) 뿐만 아닌 환경에 맞는 CI/CD 구축을 통해 개발 생산성, 협업 강화에 기여

## Projects
### 신규 프로젝트 개발 및 Devops 환경 구축

> PHP로 구축되어 있는 기존 렌터카 예약 및 백오피스 사이트를 spring 으로 리뉴얼하고 CI/CD 환경을 구축하여 보다 안정성 있는 서비스를 목표 
>
> - 참여 기간 : 2023.02 - 2023.10
> - 핵심 역할 : AWS 기반의 인프라 아키텍쳐 설계, Legacy DB 분석 및 Migration 프로세스 구현, github action 을 통한 CI/CD 구성, 외부시스템 통신을 위한 api 구현, 외부 벤더사 핸들링
> - 소속 회사 : 투어마케팅코리아
>
>> Back-end service(고객예약,백오피스,본사통신,Notication)
>> - Language : java  
>> - Skill : spring boot, JPA, mybatis
>> - as is url : https://www.alamo.co.kr/
>> 
>
>> Migration
>> - Language : PHP
>> - Skill : Mysql
>>
>> Infra
>> - Skill : ECS, ECR, docker, github action, lambda(python), AWS Dynamo Table, S3, aurora Mysql
>>

### 크롤링 수집 브라우저 개발 및 수집환경 개선

> 기존 Windows VM 에서 C# winform 으로 수집하고 있는 환경을 k8s 환경으로 전환하여 Guest OS로 인한 메모리 낭비를 절약 하고 급변하는 수집 대상에 맞게 수집환경을 확장하는 것이 목표 
> win vm 대상 약 100개 노드를 점진적 환경 변화를 위한 테스트 플랜 계획
> 20개 노드 1차 전환 후 리소스 효율 약 4배, 수집 데이터 기준 약 5배 향상
>> - 기존 vm당 4GB RAM 일 경우 4GB 당 1개의 Application -> 4개의 Pod 구성
>> - 일주일 간 수집 데이터 기준 일당 10,000건 수집 -> 50,000건 수집(windows vm 10ea / pod 10ea 비교)
> 
> - 참여 기간 : 2021.10 - 2022.11
> - 핵심 역할 : k8s cluster 설계 및 구성, puppeteer 기반 수집 브라우저 구현, workload 모니터링 체계 구축
> - 소속 회사 : 알에스엔
>
>> web crawler
>> - Language : nodejs  
>> - Skill : puppeteer, docker
>> 
>
>> Infra
>> - Skill : k8s(master node 3, worker node 20), istio, prometheus, node expoter, loki, grafana, thanos, minio
>>

### 회계 프로그램 개발(OPIC-A)

> 비영리재단, 공익회계법인에서 단식으로 관리하는 가계부 형식의 회계를 신고하기 위한 용도의 복식 형태로 출력하기 위한 프로그램으로
> 사용자는 기존의 단식처럼 입력해도 복식의 장표가 생성되고
> 자주 바뀌는 인력 교체에도 대응할 수 있도록 사용자의 편의성을 고려하는 것이 목표
>
> - 핵심 역할 : 회계로직 분석 및 설계, 회계프로그램 구현
> - 소속 회사 : 써클소프트
> - url : https://www.circlesoft.co.kr/
> - youtube : https://youtu.be/e_dNJhh6D4Y?si=Ify7_JGWpSpaYAgk
>
>> OPIC-A
>> - Language : C#  
>> - Skill : winform, devexpress, Mysql, click once
>> 
>
>> Infra
>> - Skill : azure devops
>>

### ENOVIA PLM 개발 및 운영

> 플랜트 프로젝트를 관리하는 기존 sharepoint, .net 기반 사이트를 PLM(enovia)을 적용하여 java 기반 의 사이트로 바꾸기 위한 차세대 프로젝트로 기존 SM 개발자였지만 SI 프로젝트에 참여
>
> - 핵심 역할 : VPMS 설계 및 구현
> - 소속 회사 : 도프텍
>
>> VPMS(Vendor Print Management System)
>> - Language : Java  
>> - Skill : enovia, Oracle
>> 
>

### Markup 프로그램 개발(MARKUS)

> 플랜트 프로젝트에서 도면을 유관부서들이 공유하고 Comment를 남겨 현장에 전달 전까지 검토하는 VPMS에서 시스템상에서는 pdf 로 저장되고, 각 유관부서의 엔지니어들이 각각의 설계툴이 아닌 MARKUS를 통해 보고, 의사전달을 하기 위한 툴
>
> - 핵심 역할 : VPMS 등 고객사 문서관리시스템과 연계 분석, 프로그램 구축 및 유지보수
> - 소속 회사 : 도프텍
> - 소개 url : http://www.doftech.co.kr/markus.aspx
>
>> MARKUS
>> - Language : C# WPF  
>> - Skill : MSSQL
>> 
>

### 악성코드분석 서비스 사이트, 검색엔진 구축(malwares.com)

> 대외용 분석 사이트인 malwares.com 개발
>
> - 핵심 역할 : 악성코드 탐지 사이트 백엔드 구현, 검색기능 향상을 위한 ElasticSearch 시범개발
> - 소속 회사 : 샌즈랩(구 세인트시큐리티)
> - url : https://www.malwares.com/
>
>> malwares.com
>> - Language : ASP.NET MVC  
>> - Skill : MSSQL, ElasticSearch
>> 
>

### 망연계솔루션 구축

> 고객사의 망분리 환경에서 내/외부망 사이에 파일을 교환하기 위해서 필요한 기존 보안 USB 대신 사용자 PC에 설치된 에이젼트를 통해 보다 쉽게 파일을 이동 할 수 있고, 스트림 연계를 통해 다른 서비스(메일,그룹웨어 등)들의 연계를 지원
>
> - 핵심 역할 : 고객사 서비스 및 네트워크 분석, 솔루션 구축, 관리자 웹 구현, 고객사 DB Migration(에이젼트 사용자 정보)
> - 주요 구축 사례 : 우정사업본부, KB국민은행, KB국민카드, 한국예탁결제원, 한국증권금융, 미래에셋증권, 식약청
> - 소속 회사 : SQI소프트
>
>> 관리자 웹
>> - Language : PHP  
>> - Skill : Mysql, linux
>> 
>
>> Migration
>> - Skill : java batch, Mysql, mybatis
>>
