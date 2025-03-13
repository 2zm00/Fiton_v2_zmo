

<!-- 중앙정렬 -->
<div align="center">

<img 
	align="center"
	src='assets/images/fiton_logo.png' 
	width="300"
	style="margin-right: 10px;"
/>

<h1>
	<i> Fiton v2 </i>
</h1>
<br />

<h3>Fiton_v2에서 진행했던 내용들을 리뷰합니다.</h3>
<h4> <a href="https://github.com/2zm00/Fiton_v2">프로젝트는 여기에서 확인하실 수 있습니다. 👈</a></h4>



[![Repository](https://img.shields.io/badge/Repository-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/2zm00/Fiton_v2) [![WBS](https://img.shields.io/badge/WorkBreakdownStructure-4285F4.svg?style=for-the-badge&logo=googledocs&logoColor=white)](https://docs.google.com/spreadsheets/d/1IAD58a9fe4KGy730ykC-XTgU4SGzh7CECLaEMhFYmRQ/edit?usp=drive_link) [![System-Architecture](https://img.shields.io/badge/System_Architecture-8CA1AF.svg?style=for-the-badge&logo=googledocs&logoColor=white)](https://github.com/2zm00/Fiton_v2_zmo/blob/main/assets/images/system_architecture.PNG)



[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2F2zm00&count_bg=%23BEBEBE&title_bg=%23171717&icon=tui.svg&icon_color=%23FFFFFF&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

</div>


---
## 주요 기술 스택

| 영역         | 기술 스택                                                                 |
|--------------|--------------------------------------------------------------------------|
| **[프론트엔드](pplx://action/followup)** | <img src="https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=React&logoColor=white"/>    <img src="https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>                    <img src="https://img.shields.io/badge/-Typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>  <img src="https://img.shields.io/badge/-Tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>                             |
| **[백엔드](pplx://action/followup)**    |  <img src="https://img.shields.io/badge/-Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>    <img src="https://img.shields.io/badge/-Fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>  <img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"/>                   |
| **데이터베이스** |       <img src="https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"/>  <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white"/>      |
| **인프라**       |  <img src="https://img.shields.io/badge/-AWS_S3-569A31?style=for-the-badge&logo=Amazon-s3&logoColor=white"/>  <img src="https://img.shields.io/badge/-MinIO-C72E49?style=for-the-badge&logo=MinIO&logoColor=white"/>         <img src="https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white"/>   <img src="https://img.shields.io/badge/-OCI-FF0000?style=for-the-badge&logoColor=white"/>                                    |
| **CI/CD**        | <img src="https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"/> <img src="https://img.shields.io/badge/-Github%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>  |
| **웹 서버**      | <img src="https://img.shields.io/badge/-Nginx-009639?style=for-the-badge&logo=Nginx&logoColor=white"/> |
| **AI/ML**        | <img src="https://img.shields.io/badge/-LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>  <img src="https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=white"/> <img src="https://img.shields.io/badge/-MediaPipe-0097A7?style=for-the-badge&logo=mediapipe&logoColor=white"/>                               |

---




## 프로젝트 내 역할

### 팀 리드
- WBS, Flowchart, ERD 설계, 커밋 컨벤션 문서화, API 연동 정의서, 기능 명세서, GithubProject Milestone을 통해 팀원들과의 협업 커뮤니케이션을 이끌었습니다.
<div align="center">
<img width="300" src="/assets/images/milestone.PNG"/>
<img width="300" src="/assets/images/user_flowchart.png"/>
<img width="300" src="/assets/images/process_flowchart.png"/>
</div>

### 프론트엔드 
- React, Next.js 기반 개발 환경 구축하고 반응형 UI/UX를 설계하였습니다.
- RestAPI 연동과 훅을 이용한 상태관리를 구현하였습니다.
- SEO 최적화 및 성능을 개선하였습니다.
<div align="center">
<img width="300" src="/assets/images/ui.png"/>
<img width="300" src="/assets/images/ins_list.png"/>
</div>

### 백엔드
- FastAPI 기반 AI 모델 API와 운동자세 분석 기능을 구현하여 성능 최적화와 데이터 처리속도 개선했습니다.
- Langchain과 HuggingFace 기반 AI 챗봇 서비스를 개발하였습니다.
- Google Mediapipe 기반 운동 자세 분석 기능을 도입하였습니다.

	(비동기 처리 지원으로 기존 Django 사용 대비 응답시간 40% 단축, 초당 처리량 300% 향상,  20% 메모리 사용량 절감 )
<div align="center">
<img width="800" src="/assets/images/analyze.png"/>
</div>



### 인프라
- 프론트엔드/스토리지 서버를 AWS EC2로 운영하였습니다. AWS S3 스토리지 비용문제 이슈를 MinIO를 도입하여 비용을 절감했습니다.


	( 월 23$의 비용을 0$으로 절감 매 월 1TB 스토리지 100만 GET 요청 EC2 프리티어 인스턴스 기준)
- MSA 아키텍처를 구조를 아키텍처 구조를 통해 애자일하게 관리했습니다. 

	(프론트엔드 / 백엔드 / 데이터베이스 / 스토리지)
- TDD 기반 모킹 데이터를 통해 안정적인 아키텍처를 구축했습니다.
### CI/CD
- Github Actions를 활용한 CI/CD 파이프라인을 구현하였습니다.
- Docker 컨테이너 기반 배포 프로세스를 구축하여 배포 장애율이 66% 감소하였습니다. 

	(배포시간이 평균 1800s 에서 600s으로 단축)

- GitHub Pull Request 기반 코드 리뷰 과정에서 ChatGPT 자동화 코드 리뷰 기능을 도입하였습니다.

	(PR당 평균 리뷰 시간을 180분에서 30분(70%)으로 감소)
<div align="center">
<img width="300" src="/assets/images/code_review.png"/>
</div>

---




## 기술문서화
- WBS 

	(API 연동 정의서, 기능 명세서 등을 확인하 실 수 있습니다.)
<div align="center">


[![WBS](https://img.shields.io/badge/WorkBreakdownStructure-4285F4.svg?style=for-the-badge&logo=googledocs&logoColor=white)](https://docs.google.com/spreadsheets/d/1IAD58a9fe4KGy730ykC-XTgU4SGzh7CECLaEMhFYmRQ/edit?usp=drive_link)

</div>

- 시스템 아키텍처
```mermaid
flowchart LR
    %% 브라우저 아이콘들
    Browsers[("Chrome/Firefox/Safari")] --> NEXT
    
    %% FE 서버
    subgraph AWS_FE["aws FE서버"]
        subgraph Docker1["Docker"]
            subgraph NEXT["NEXT.js"]
                Tailwind["Tailwind CSS"]
                React["React"]
            end
            
            NGINX["NGINX"]
            MinIO["MinIO"]
        end
    end
    
    %% BE 서버 - Django
    subgraph BE_Django["BE서버"]
        subgraph Docker2["Docker"]
            subgraph Django["django"]
                DjangoFramework["Django"]
                DRF["Django REST framework"]
            end
            Postgres["PostgreSQL"]
        end
    end
    
    %% BE 서버 - FastAPI
    subgraph AWS_BE["aws BE서버"]
        subgraph Docker3["Docker"]
            FastAPI["FastAPI"]
        end
    end
    
    %% 외부 서비스
    HuggingFace["Hugging Face"]
    LangChain["LangChain"]
    MediaPipe["MediaPipe"]
    
    %% 연결
    NEXT --> NGINX
    NGINX --> Gunicorn["Gunicorn"]
    NGINX --> Unicorn["Unicorn"]
    MinIO <--> NEXT
    Gunicorn --> Django
    Unicorn --> FastAPI
    Django --> Postgres
    FastAPI --> HuggingFace
    FastAPI --> LangChain
    FastAPI --> MediaPipe

```

- Github Project Milestone 작성
<div align="center">
<img width="300" src="/assets/images/milestone.PNG"/>
</div>

- FlowChart 작성
<div align="center">
<img width="300" src="/assets/images/user_flowchart.png"/>
<img width="300" src="/assets/images/process_flowchart.png"/>
</div>
