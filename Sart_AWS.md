

## ☁️ AWS 클라우드 컴퓨팅 입문 및 핵심 서비스 활용 과정 (세부 목차)

---

### I. 클라우드 컴퓨팅 및 AWS 기본 개념 📚

1.  **클라우드 컴퓨팅의 정의 및 모델 이해**
    * 1.1. 클라우드 컴퓨팅의 개념과 등장 배경
    * 1.2. 온프레미스(On-Premise)와 클라우드의 비용/운영 비교
    * 1.3. 서비스 모델의 이해: IaaS, PaaS, SaaS
    * 1.4. 클라우드 배포 모델: Public, Private, Hybrid Cloud

2.  **AWS 글로벌 인프라 구조 및 장점**
    * 2.1. AWS 리전(Region)과 가용 영역(AZ)의 역할과 중요성
    * 2.2. 고가용성(HA) 및 재해 복구(DR) 전략 기초
    * 2.3. 엣지 로케이션(Edge Location)과 콘텐츠 전송 네트워크(CDN) 소개 (Amazon CloudFront)

3.  **AWS 계정 생성 및 콘솔 기본 활용**
    * 3.1. AWS 계정 생성 및 **[프리티어(Free Tier)]** 활용 가이드
    * 3.2. **AWS Management Console** 주요 기능 및 대시보드 둘러보기
    * 3.3. AWS CLI(Command Line Interface) 및 SDK 소개 (접근 방법 개요)

---

### II. 보안, 권한 및 비용 관리 기초 (클라우드의 핵심) 🔑💰

4.  **클라우드 보안과 공동 책임 모델의 이해**
    * 4.1. **AWS 공동 책임 모델**의 상세 설명 (클라우드 vs. 고객 책임 영역 구분)
    * 4.2. 클라우드 '아래'의 보안: 물리적 보안 및 AWS 인프라 보호
    * 4.3. 클라우드 '안'의 보안: 사용자 데이터, 설정, OS 패치 책임

5.  **IAM (Identity and Access Management)을 이용한 접근 관리**
    * 5.1. **루트 사용자** vs. **IAM 사용자** 분리 및 2FA(다단계 인증) 설정
    * 5.2. IAM **정책(Policy)** 구조 이해 및 **최소 권한 원칙** 적용
    * 5.3. IAM **그룹** 및 **역할(Role)**을 활용한 권한 위임 실습

6.  **AWS 요금 체계 및 비용 최적화 기초**
    * 6.1. AWS의 3가지 기본 결제 방식 (Pay-as-you-go, Reserved Instances, Savings Plans) 비교
    * 6.2. **[AWS 요금 계산기]**를 활용한 예상 비용 산출 실습
    * 6.3. **AWS Cost Explorer** 및 **AWS Budgets**를 이용한 비용 모니터링 기초
    * 6.4. **태그(Tagging)**를 활용한 리소스 및 비용 관리 전략

---

### III. 핵심 서비스 활용: 컴퓨팅, 스토리지, 네트워킹 🚀

7.  **Amazon EC2 (Elastic Compute Cloud)를 이용한 서버 구축**
    * 7.1. EC2 인스턴스 타입 및 AMI(Amazon Machine Image) 선택 전략
    * 7.2. EC2 인스턴스 생성 및 SSH(Key Pair)를 이용한 접속 실습
    * 7.3. **보안 그룹(Security Group)** 설정 및 인바운드/아웃바운드 규칙 이해
    * 7.4. 탄력적 IP(EIP) 및 **[Cloud-Init]**을 활용한 초기 설정 자동화 (개요)

8.  **스토리지 서비스 (S3, EBS)의 활용**
    * 8.1. **S3 (Simple Storage Service)** 버킷 생성 및 정적 웹사이트 호스팅 실습
    * 8.2. S3의 객체 스토리지 개념 및 스토리지 클래스 (Standard, IA, Glacier) 비교
    * 8.3. **EBS (Elastic Block Store)**의 역할 및 EC2와의 연결 이해
    * 8.4. EBS 스냅샷을 활용한 백업 및 복구 기초

9.  **VPC (Virtual Private Cloud)를 통한 가상 네트워크 구성**
    * 9.1. VPC 개념 및 기본 구성 요소 (CIDR, 라우팅 테이블, IGW)
    * 9.2. **서브넷(Subnet)**의 이해 (Public Subnet과 Private Subnet의 역할)
    * 9.3. **NAT Gateway**를 이용한 Private Subnet의 외부 통신 (개요)
    * 9.4. 실습: 2-Tier 아키텍처 (Web/DB) 네트워크 설계 (다이어그램 위주)

10. **관리형 데이터베이스 서비스 (RDS, DynamoDB) 소개**
    * 10.1. **RDS (Relational Database Service)**의 이점 및 DB 엔진 선택
    * 10.2. RDS 인스턴스 생성 및 기본 접속 실습 (Multi-AZ 개념 소개)
    * 10.3. **DynamoDB** (NoSQL)의 개념 및 관계형 DB와의 차이점

---

### IV. 운영, 확장 및 아키텍처 기본 원칙 📊

11. **운영 및 모니터링 도구 활용**
    * 11.1. **CloudWatch**를 이용한 리소스 **메트릭(Metric)** 확인 및 성능 모니터링
    * 11.2. CloudWatch **알람(Alarm)** 설정 및 이벤트 기반 자동화 기초
    * 11.3. CloudTrail을 이용한 계정 활동 로깅 및 보안 감사 (개요)

12. **확장성 및 자동화 서비스 개요**
    * 12.1. **Auto Scaling**의 개념 및 고가용성/확장성 이점
    * 12.2. **ELB (Elastic Load Balancing)**의 역할 및 트래픽 분산 원리
    * 12.3. **Lambda**를 이용한 서버리스(Serverless) 컴퓨팅 개념 소개

13. **AWS Well-Architected Framework 소개**
    * 13.1. **5가지 설계 원칙** (보안, 운영 우수성, 안정성, 성능 효율성, 비용 최적화)
    * 13.2. 이 원칙이 **IT 전략 계획(ITSP)** 및 아키텍처 설계에 미치는 영향
    * 13.3. **실습 마무리:** 프리티어 환경에서 구축한 리소스 완전 삭제 및 비용 확인

이 세부 목차를 통해 수강생들은 단순히 도구 사용법을 넘어, 클라우드 환경의 **보안, 비용, 아키텍처**라는 3가지 핵심 축을 균형 있게 이해할 수 있을 것입니다. 강의 시 중요한 개념은 **굵게 강조**하고, 출처가 될 수 있는 주요 서비스나 문서는 **하이퍼링크 형식**으로 제공하는 것을 잊지 마십시오!
