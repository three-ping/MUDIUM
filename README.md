# MUDIUM

   <img src="docs/img/로고.png" width="400" height="250" alt="로고이미지">

| 뮤지컬 커뮤니티


## 🤝TEAM
| <img src="docs/img/profile/김시우.png" width="200" height = "160">|<img src="docs/img/profile/이효진.png" width="200" height = "160">|<img src="docs/img/profile/김서현.png" width="200" height = "160">|<img src="docs/img/profile/이우진.jpeg" width="200" height = "160">|<img src="docs/img/profile/김동혁.jpg" width="200" height = "160">|<img src="docs/img/profile/김정모.jpg" width="200" height = "160"> |
| :------------------------------------: | :-----------------------------------: | :-----------------------------------: | :--------------------------------------: | :-----------------------------------: | :------------------------------------------: |
| [김시우](https://github.com/siu98) | [이효진](https://github.com/jinjin0528) | [김서현](https://github.com/1etterh) | [이우진](https://github.com/Vorschlag-bit) | [김동혁](https://github.com/dongkh9) | [김정모](https://github.com/mojeeeeong) |

## 🛠️기술스택
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![SpringBoot](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Vue.js](https://img.shields.io/badge/vue3-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)

## 📢협업 툴
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## 📋전체 프로젝트 일정
**프로젝트 일정 : 2024년 10월 14일 ~ 2024년 10월 21일**

### 목차

- [1. 프로젝트 개요](#1-프로젝트-개요)
- [2. 요구사항 명세서](#2-요구사항-명세서)
- [3. WBS](#3-WBS)
- [4. DDD](#4-DDD)
- [5. DB 모델링](#5-DB-모델링)
- [6. UI 설계](#6-UI-설계)
- [7. CI/CD 파이프라인](#7-CI-CD-파이프라인)
- [8. 프론트엔드 및 백엔드 테스트 결과](#8-프론트엔드-백엔드-테스트-결과)
- [9. CI/CD 테스트 결과](#9-CI-CD-테스트-결과)
- [10. 팀 회고](#10-팀-회고)

---
## 🍀1. 프로젝트 개요

뮤지컬 관련 정보를 확인하고 공유하며 소통하는 커뮤니티입니다.

### 1.1 프로젝트 소개

**뮤지컬에 대해 자유롭게 정보를 공유하고 소통해보세요.**

- ✔️ 관람했던 뮤지컬 티켓을 온라인으로 소장해보세요.
- ✔️ 다른 사람들이 좋아하는 뮤지컬을 확인해보세요.
- ✔️ 뮤지컬 리뷰를 확인하고 공유해보세요.
- ✔️ 뮤지컬 테마의 캘린더로 뮤지컬 일정을 확인하세요.


---

### 1.2 프로젝트 배경

뮤지컬 산업은 최근 몇 년간 빠르게 성장하며, 많은 관객들이 뮤지컬에 대한 정보를 찾고 소통하고자 하는 수요가 높아지고 있습니다. 그러나 기존의 정보 제공 플랫폼은 사용자가 뮤지컬에 대해 자유롭게 논의하고 소통할 수 있는 커뮤니티 기능이 부족한 상황입니다. 이에 따라, 뮤지컬을 사랑하는 사람들이 한데 모여 정보 공유, 리뷰 작성, 티켓 소장 등 다양한 활동을 할 수 있는 공간을 마련하고자 이 프로젝트를 기획하게 되었습니다.

![2023년 뮤지컬 통계자료](docs/img/2023_뮤지컬_통계.png)

   [출처] 예술경영지원센터 <2023년 공연시장 티켓판매 현황 분석 보고서(총결산)>


---

### 1.3 국내외 유사 서비스와 차별성

#### 1.3.1 플레이DB
국내 대표적인 공연 정보 제공 서비스로, 뮤지컬 정보와 리뷰를 제공합니다. 하지만 UI가 사용자 친화적이지 않고, 커뮤니티 기능이 극히 제한적입니다. 뮤지컬에 대한 정보를 얻을 수는 있지만, 회원 간의 공유는 활발하지 않습니다.

![플레이디비_커뮤니티](./docs/img/플레이디비.png)

[플레이디비의 커뮤니티 - 회원 간 정보 공유를 위한 공간이 존재하지 않습니다.]

#### 1.3.2 뮤디엄 MUDIUM
뮤디엄은 MUSICAL과 MEDIUM, MUSEUM을 합성한 단어입니다. 박물관(Museum)은 예술, 역사, 문화의 중요한 매개체로서 과거와 현재를 연결하며 사람들에게 지식을 전달하죠. 이와 유사하게 뮤디움은 뮤지컬을 매개하는 플랫폼으로서, 뮤지컬이라는 예술 형태를 대중에게 소개하고 경험을 공유하는 역할을 합니다.

따라서, 뮤디움은 뮤지컬이라는 예술적 경험을 하나의 박물관처럼 보존하고, 다양한 정보를 사람들에게 제공하는 디지털 매체로 기능할 수 있습니다. 마치 박물관이 작품을 전시하고 공유하는 것 처럼, 뮤디움은 뮤지컬에 대한 정보, 현재의 흐름, 그리고 미래의 가능성을 모두 담아내는 뮤지컬의 박물관 같은 역할을 한다는 개념을 담고자 합니다.

또한 뮤디움은 매개체(MEDIUM)로서의 역할을 할 수 있습니다. 뮤지컬을 사랑하는 사람들이 모여 각자의 의견을 공유하고, 좋은 작품을 추천하며 소통합니다.

이렇게 뮤디움은 뮤지컬을 단순히 즐기는 것이 아니라, 뮤지컬에 대한 정보를 공유하고 의견을 나눌 수 있는 커뮤니티가 되고자 합니다.

## 🍀2. 요구사항 명세서

   ![요구사항명세서](./docs/img/요구사항명세서.png)


---

## 🍀3. WBS

   ![WBS](./docs/img/WBS.png)

---

## 🍀4. DDD
### 4.1 Domain Event Deduction
![Domain Event Deduction](./docs/img/ddd/1단계.png)

### 4.2 External System
![Domain Event Deduction](./docs/img/ddd/2단계.png)

### 4.3 Command
![Domain Event Deduction](./docs/img/ddd/3단계.png)

### 4.4 Actor
![Domain Event Deduction](./docs/img/ddd/4단계.png)

### 4.5 Aggregate
![Domain Event Deduction](./docs/img/ddd/5단계.png)

### 4.6 Bounded Context
![Domain Event Deduction](./docs/img/ddd/6단계.png)

### 4.7 Bounded context
![Domain Event Deduction](./docs/img/ddd/7단계.png)

#### 4.7.1 Bounded context - 1차 구현 목표
![Domain Event Deduction](./docs/img/ddd/7단계_1차목표.png)


---

## 🍀5. DB 모델링
---
### 5.1 논리 모델링

![논리모델링](./docs/img/논리.png)
--- 
### 5.2 물리 모델링
![물리모델링](./docs/img/물리.png)
---

## 🍀6. UI 설계
![피그마](./docs/img/figma.png)

---

## 🍀7. CI/CD 파이프라인
![파이프라인](./docs/img/아키텍처.png)
<details>
<summary>jenkins script code</summary>
   
   ```
   pipeline {
       agent any
   
       tools {
           gradle 'gradle'
           jdk 'openJDK17'
       }
   
       environment {
           DOCKERHUB_CREDENTIALS = credentials('DOCKERHUB_PASSWORD')
           DOCKERHUB_USERNAME = '1etterh'
           GITHUB_URL = 'https://github.com/three-ping/MUDIUM_DevOps.git'
       }
   
       stages {
           stage('Preparation') {
               steps {
                   script {
                       if (isUnix()) {
                           sh 'docker --version'
                       } else {
                           bat 'docker --version'
                       }
                   }
               }
           }
           stage('Source Build') {
               steps {
                   git branch: 'main', url: "${env.GITHUB_URL}"
                   script {
                       if (isUnix()) {
                           sh "chmod +x ./gradlew"
                           sh "./gradlew clean build"
                       } else {
                           bat "gradlew.bat clean build"
                       }
                   }
               }
           }
           stage('Container Build and Push') {
               steps {    
                   script {
                       withCredentials([usernamePassword(credentialsId: 'DOCKERHUB_PASSWORD', usernameVariable: 'DOCKER_USER', passwordVariable: 'DOCKER_PASS')]) {
                           if (isUnix()) {
                               sh "cp ./build/libs/*.jar ."
                               sh "docker build -t ${DOCKERHUB_USERNAME}/test-pipe2:latest ."
                               sh "docker login -u ${DOCKER_USER} -p ${DOCKER_PASS}"
                               sh "docker push ${DOCKERHUB_USERNAME}/test-pipe2:latest"
                           } else {
                               bat "copy .\\build\\libs\\*.jar ."
                               bat "docker build -t ${DOCKERHUB_USERNAME}/test-pipe2:latest ."
                               bat "docker login -u %DOCKER_USER% -p %DOCKER_PASS%"
                               bat "docker push ${DOCKERHUB_USERNAME}/test-pipe2:latest"
                           }
                       }
                   }
               }
           }
       }
   
       post {
           always {
               script {
                   if (isUnix()) {
                       sh 'docker logout'
                   } else {
                       bat 'docker logout'
                   }
               }
           }
           success {
               echo 'Pipeline succeeded!'
           }
           failure {
               echo 'Pipeline failed!'
           }
       }
   }
   ```
   
</details>


---

## 🍀8. 프론트엔드 및 백엔드 테스트 결과

---
### 8.1 자유게시글

<details>
  <summary>자유게시글</summary>

  - <details>
     
      <summary>자유게시글 목록 조회</summary>
     
    ![테스트](./docs/gif/board/자유게시글목록.gif)
    
    </details>

  - <details>
     
      <summary>자유게시글 검색</summary>
     
      ![테스트](./docs/gif/board/자유게시글검색.gif)
    
    </details>

  - <details>
      <summary>자유게시글 상세 조회</summary>
     ![테스트](./docs/gif/board/자유게시글상세조회.gif)
    </details>

  - <details>
      <summary>자유게시글 작성</summary>
     
      ![테스트](./docs/gif/board/자유게시글작성.gif)
    </details>

   - <details>
      <summary>자유게시글 수정</summary>
     
      ![테스트](./docs/gif/board/자유게시글수정.gif)
    </details>

   - <details>
      <summary>자유게시글 삭제</summary>
     
      ![테스트](./docs/gif/board/자유게시글삭제.gif)
    </details>

   - <details>
      <summary>자유게시글 댓글 작성</summary>
     
      ![테스트](./docs/gif/board/자유게시글댓글작성.gif)
    </details>

   - <details>
      <summary>자유게시글 댓글 수정</summary>
     
      ![테스트](./docs/gif/board/자유게시글댓글수정.gif)
    </details>

   - <details>
      <summary>자유게시글 댓글 삭제</summary>
     
      ![테스트](./docs/gif/board/자유게시글댓글삭제.gif)
    </details>

   - <details>
      <summary>자유게시글 대댓글 작성</summary>
     
      ![테스트](./docs/gif/board/자유게시글대댓글작성.gif)
    </details>

   - <details>
      <summary>자유게시글 대댓글 수정</summary>
     
      ![테스트](./docs/gif/board/자유게시글대댓글수정.gif)
    </details>

   - <details>
      <summary>자유게시글 대댓글 삭제</summary>
     
      ![테스트](./docs/gif/board/자유게시글대댓글삭제.gif)
    </details>

   - <details>
      <summary>자유게시글 백엔드 </summary>
     
      ![테스트](./docs/gif/board/자유백엔드.gif)
    </details>

   - <details>
      <summary>자유게시글 댓글 백엔드</summary>
     
      ![테스트](./docs/gif/board/자유댓글백엔드.gif)
    </details>

   - <details>
      <summary>자유게시글 대댓글 백엔드</summary>
     
      ![테스트](./docs/gif/board/자유대댓글백엔드.gif)
    </details>

   - <details>
      <summary>자유게시글 좋아요 백엔드</summary>
     
      ![테스트](./docs/gif/board/자유좋아요백엔드.gif)
    </details>

</details>

---

### 8.2 공지게시글

<details>
  <summary>공지게시글</summary>

  - <details>
     
      <summary>공지게시글  조회</summary>
     
    ![테스트](./docs/gif/board/공지게시글조회.gif)
    
    </details>

  - <details>
     
      <summary>공지게시글 백엔드</summary>
     
      ![테스트](./docs/gif/board/공지백엔드.gif)
    
    </details>

</details>

---

### 8.3 가이드북
<details>
  <summary>가이드북 메인(입문 작품 추천 / 뮤지컬 용어 안내 / 뮤지컬 관람 매너)</summary>
   
   - <details>
      <summary>입문 작품 추천 백엔드</summary>
      
      <details>
         <summary>입문 작품 추천 전체 조회</summary>
         
        ![테스트](./docs/img/guidebook_img/작품추천목록.png)
     
      </details>
      
      <details>
        <summary>입문 작품 추천 상세 조회</summary>
         
        ![테스트](./docs/img/guidebook_img/작품추천상세조회.png)
     
      </details>
      
      <details>
        <summary>입문 작품 추천 작성</summary>
         
        ![테스트](./docs/img/guidebook_img/작품추천작성.png)
     
      </details>
      
      <details>
        <summary>입문 작품 추천 수정</summary>
         
        ![테스트](./docs/img/guidebook_img/작품추천수정.png)
     
      </details>
      
     </details>
    
   - <details>
         <summary>뮤지컬 용어 안내 백엔드</summary>
         <details>
           <summary>뮤지컬 용어 안내 전체 조회</summary>
            
        ![테스트](./docs/img/guidebook_img/용어목록.png)
      </details>
      
      <details>
        <summary>뮤지컬 용어 안내 상세 조회</summary>
         
        ![테스트](./docs/img/guidebook_img/용어상세.png)
      </details>
      <details>
        <summary>뮤지컬 용어 안내 작성</summary>
         
        ![테스트](./docs/img/guidebook_img/용어작성.png)
      </details>
      <details>
        <summary>뮤지컬 용어 안내 수정</summary>
         
        ![테스트](./docs/img/guidebook_img/용어수정.png)
      </details>
   
   - <details>
      <summary>관람 매너 안내 백엔드</summary>
      <details>
        <summary>관람 매너 안내 전체 조회</summary>
         
        ![테스트](docs/img/guidebook_img/매너목록.png)
      </details>
      <details>
        <summary>관람 매너 안내 상세 조회</summary>
         
        ![테스트](./docs/img/guidebook_img/매너상세조회.png)
      </details>
      <details>
        <summary>관람 매너 안내 작성</summary>
         
        ![테스트](./docs/img/guidebook_img/매너작성.png)
      </details>
      <details>
        <summary>관람 매너 안내 수정</summary>
         
        ![테스트](./docs/img/guidebook_img/매너수정.png)
      </details>
   </details>
   <details>
   <summary>가이드북 프론트</summary>
      
   ![테스트](./docs/gif/guidebook/가이드북.gif)
   
   </details>
</details>
</details>

---
### 8.4 리뷰

<details>
  <summary>리뷰</summary>

  - <details>
     
      <summary>리뷰 전체 조회</summary>
     
    ![테스트](./docs/gif/review/review_total.gif)
    
    </details>

  - <details>
     
      <summary>리뷰 상세 조회</summary>
     
    ![테스트](./docs/gif/review/review_detail.gif)
    
    </details>

  - <details>
     
      <summary>리뷰 작성</summary>
     
    ![테스트](./docs/gif/review/review_regist.gif)
    
    </details>

  - <details>
     
      <summary>리뷰 수정</summary>
     
    ![테스트](./docs/gif/review/review_update.gif)
    
    </details>

  - <details>
     
      <summary>리뷰 삭제</summary>
     
    ![테스트](./docs/gif/review/review_delete.gif)
    
    </details>

  - <details>
     
      <summary>리뷰 좋아요</summary>
     
    ![테스트](./docs/gif/review/review_like.gif)
    
    </details>

  - <details>
     
      <summary>리뷰 백엔드</summary>
     
      ![테스트](./docs/gif/review/review_backend.gif)
    
    </details>

</details>

---

### 8.5 비밀리뷰

<details>
  <summary>비밀리뷰</summary>

  - <details>
     
      <summary>비밀리뷰 조회</summary>
     
    ![테스트](./docs/gif/secret-review/secret_review_view.gif)
    
    </details>

  - <details>
     
      <summary>비밀리뷰 작성</summary>
     
    ![테스트](./docs/gif/secret-review/secret_review_regist.gif)
    
    </details>

  - <details>
     
      <summary>비밀리뷰 수정</summary>
     
    ![테스트](./docs/gif/secret-review/secret_review_update.gif)
    
    </details>

  - <details>
     
      <summary>비밀리뷰 백엔드</summary>
     
      ![테스트](./docs/gif/secret-review/secret_review_backend.gif)
    
    </details>

</details>

---

### 8.6 캘린더

<details>
  <summary>캘린더</summary>

  - <details>
     
      <summary>캘린더 테마 조회</summary>
     
    ![테스트](./docs/gif/calendar/캘린더테마.gif)
    
    </details>
</details>

---

### 8.7 커스텀 티켓 
<details>
  <summary>커스텀티켓</summary>
   <details>
     <summary>커스텀티켓 생성</summary>
     <img src="./docs/gif/customticket/customticketCreate.gif" alt="테스트">

   </details>

   <details>
     <summary>커스텀티켓 생성 백엔드</summary>
     <img src="./docs/gif/customticket/customticketCreateTest.gif" alt="테스트">

   </details>

   <details>
     <summary>커스텀티켓 조회</summary>
      <img src="./docs/gif/customticket/customticket.gif" alt="테스트">

   </details>

   <details>
     <summary>커스텀티켓 조회 백엔드</summary>
     <img src="./docs/gif/customticket/customticketTest.gif" alt="테스트">

   </details>

   <details>
     <summary>커스텀티켓 삭제</summary>
     <img src="./docs/gif/customticket/customticketDelete.gif" alt="테스트">
   </details>

   <details>
     <summary>커스텀티켓 삭제 백엔드</summary>
     <img src="./docs/gif/customticket/customticketDeleteTest.gif" alt="테스트">
   </details>
</details>

---

### 8.8 뮤지컬 정보
<details>
  <summary>뮤지컬 정보</summary>
   <details>
     <summary>뮤지컬 조회</summary>
     <img src="./docs/gif/musicalInfo/musical-select.gif" alt="테스트">

   </details>

   <details>
     <summary>뮤지컬 조회 백앤드</summary>
     <img src="./docs/gif/musicalInfo/back-find.gif" alt="테스트">

   </details>

   <details>
     <summary>뮤지컬 검색</summary>
     <img src="./docs/gif/musicalInfo/musical-search.gif" alt="테스트">

   </details>

   <details>
     <summary>뮤지컬 검색 백엔드</summary>
     <img src="./docs/gif/musicalInfo/back-titlesearch.gif" alt="테스트">

   </details>
</details>

---

### 8.9 별점
<details>
  <summary>별점</summary>
   <details>
     <summary>별점 생성</summary>
     <img src="./docs/gif/scope/scope-create.gif" alt="테스트">

   </details>

   <details>
     <summary>별점 생성 백엔드</summary>
     <img src="./docs/gif/scope/back-scopecreate.gif" alt="테스트">

   </details>

   <details>
     <summary>별점 수정</summary>
      <img src="./docs/gif/scope/scope-save.gif" alt="테스트">

   </details>

   <details>
     <summary>별점 수정 백엔드</summary>
     <img src="./docs/gif/scope/back -scopeupdate.gif" alt="테스트">

   </details>

   <details>
     <summary>평균 별점 조회</summary>
     <img src="./docs/gif/scope/scope-create.gif" alt="테스트">
   </details>

   <details>
     <summary>평균 별점 조회 백앤드</summary>
     <img src="./docs/gif/scope/back -average.gif" alt="테스트">
   </details>
</details>


## 🍀9. CI/CD 테스트 결과
<details>
   <summary>결과</summary>
   
   ![파이프라인](./docs/gif/pipeline.gif)

</details>

---

## 🍀10. 팀 회고
#### 김시우
> **이효진**: 덕분에 프론트 믿고 갔습니다!! 묵묵히 화면 구현해내시고 덕분에 저희 조의 kick! 멋있는 홀로그램을 볼 수 있었습니다. 다음 프로젝트때 더 멋있는 화면 기대하겠습니다!!!
> 

> **김서현**: 우리 프로젝트의 핵심 기능 중 하나인 커스텀 티켓을 구현해주신 덕분에 프로젝트 진행이 수월해진 것 같습니다. 피그마도 잘 만들어주셔서 준비해주신 틀을 토대로 완성도 높은 UI를 만들 수 있었습니다. 정말 고생 많으셨습니다!

> **이우진**: 명실상부 프론트 고수.. 백실력도 훌륭하시지만 프론트에 관해서 모르는 게 있으면 언제나 친절히 알려주시며 우리 프로젝트의 kick이었던 회원 고유 티켓을 구현하시면서 정말 수고가 많으셨다.. 특유의 디자인 감각이 뛰어나셔서 디자인에 관해 컨펌도 종종 해주셔서 감사하다.
> 

> **김동혁**: 프로젝트 내내 디자인 부분에서 뛰어난 감각을 보여주셔서 큰 도움이 되었습니다. 난이도가 높은 부분들을 구현하시느라 고생 많으셨습니다! 늘 침착하게 소통하시는 모습에서 많이 보고 배웁니다.
>

> **김정모**: 피그마부터 프론트엔드까지의 구성력이 정말 뛰어나셨습니다. 프론트 개발에서의 가장 중요한 부분들을 잘 해결해 주셔서, 백엔드와의 통신에만 집중할 수 있었습니다. 작업 중에는 서로 질문도 많이 주고받으며, 프로젝트가 어떻게 진행되는지 끊임없이 확인할 수 있었습니다. 그 덕분에 팀에 자연스럽게 녹아들어 큰 도움이 되신 것 같아요. 시우님은 백엔드 쪽 개발은 많이 못한 것 가지만, 실제로 코드를 분석해보니 고려할 점들이 참 많았고, 생각해야할 것이 많았는데 어떻게 타파해야할지 항상 생각하고 있는 것 같습니다. 그리고 프론트까지도 책임감 있게 맡아서 진행하시는 모습, 정말 대단합니다!
>

#### 이효진
> **김시우**:도메인을 3개나 맡으셨습니다. 특히 모든 부분이 범위가 넒어서 힘들어 하시는 모습을 보았습니다. 그러나 백엔드 및 프론트엔드의 모든 부분을 직접 완성하였습니다. 특히, 캘린더에 AI 이미지를 추가하는 부분을 힘들어 하셨는데 예쁘게 완성해주셨습니다!
> 

> **김서현**: 저희 팀의 핵심 기능중 하나인 캘린더를 예쁘게 잘 만들어주셔서 감사했습니다. 항상 저희 팀의 중심이 되어 사람들에게 활력을 주시는 팀장님이십니다. 효진님의 리더십 덕분에 팀원들의 단합력이 높아져서 다같이 열심히 프로젝트를 할 수 있었던 것 같습니다! 정말 고생하셨습니다


> **이우진**:  백에 대해서 자신감이 조금 없으신데, 이해할 수 없다. 홀로 3개의 도메인을 백과 프론트 모두 완벽하게 구현하셨다. 맡은 바를 묵묵히 수행하시는 우리 팀장님.. 존경합니다.
> 

> **김동혁**: 꼼꼼하게 맡은 부분을 해내시는 모습에서 책임감과 성실함이란 무엇인지 배울 수 있었습니다. 앞으로 2달간 진행될 최종 프로젝트에서 저도 그러한 성실함을 가지고 팀 활동에 임하겠습니다!
>

> **김정모**: 시간이 지날수록 점점 더 편안하게 소통할 수 있었고, 자연스럽게 서로 많은 도움을 주고받았던 것 같습니다. 효진님이 맡은 도메인에서 해야할 것들의 범위가 생각보다 넓었고, 진행 과정에서 꽤나 많은 어려움과 마주한 모습을 보았는데요. 그런 모습을 보면서 괜히 걱정도 했지만, 결국에는 모든 문제를 훌륭하게 해결하셨습니다. 프로젝트가 끝날 무렵에는 저를 비롯한 다른 조원들까지 도와주는 든든한 존재로 자리 잡으셨습니다. 그 과정을 지켜보면서 정말 큰 성장과 헌신을 느낄 수 있었습니다!
>

#### 김서현
> **이효진**: 서현님 덕분에 회원에 젠킨스까지 해낼 수 있었습니다. 다들 어려워하던 데브옵스를 침착히 해내시고 감사합니다!! 비공자자 밭에 유일한 전공자라 부담을 가질 실만도 한데 저희가 물어보면 친절하게 알려주셔서 감사합니다!!
> 

> **김시우**:  주제 선정부터 개발까지 모든 부분에서 다양한 아이디어를 제시해 주었습니다. (특히 프로젝트의 kick이 었던 회원 고유 티켓) 또한, 가장 어려운 회원 도메인 맡으셨는데 예상대로 완벽하게 구현해주셨습니다!
> 

> **이우진**:  전공자 출신답게 탄탄한 기본기가 정말 대단하시다! 프론트, 백, db 모두 잘 알고 계시며 프로젝트에 가장 힘든 부분 중 하나인 회원과 배포를 담당하셔서 수고가 정말 정말 많으셨다… 파이널땐 더 열심히해서 수고를 조금이라도 덜어드리고 싶다.
> 

> **김동혁**: 수업시간에 다루지 않은 부분까지 잘 구현하셔서 더 많은 것들을 할 수 있었습니다. 앞으로의 프로젝트에서도 잘 따라갈 수 있도록 노력하겠습니다!
>

> **김정모**: 역시 실력자라는 말이 딱 맞습니다! 다양한 아이디어를 제시해주실 때마다, 머릿속에서 이미 모든 계획이 그려져 있는 듯한 느낌을 받았습니다. 서현님이 설명해주시는 프로젝트 방향을 들으면서 점점 더 명확해지는 프로젝트의 구조를 보며, 서현님의 뛰어난 사고력에 감탄하지 않을 수 없었습니다. 회원 도메인을 맡겠다고 하셨을 때, 충분히 잘 해낼 거라고 믿었는데, 그 기대에 완벽하게 부응하셨습니다. 역시 실력자…대단하십니다!!!

#### 이우진
> **김시우**: 뮤지컬 및 공연 정보를 담당하셨는데 생각보다 api가 제공하는 범위가 좁아서 힘드셨을텐데 돌파구를 찾아서 구현해주셔서 저희의 메인 페이지가 나올 수 있었던 것 같습니다. 추가로 별점 부분도 해주셨는데 끝까지 반개 별점 구현해주셔서 감사합니다!
> 

> **이효진**: 개발 초입부터 혼자서 묵묵히 api가져와 정보 제공해주시는데 큰 힘을 주셨어요!! 우진님 아니셨으면 정보를 가져와 저희가 구상해낸 모든 것들을 이뤄내기 힘들었을 겁니다!! 또한 많은 부분들을 도맡아서 하시느라 너무너무 고생하셨습니다!!
> 

> **김서현**: 개인적으로 가장 어려운 부분이라고 생각했던 외부 API와의 통신을 맡으셨습니다. 수업시간에 배우지 않은 어려운 부분을 혼자의 힘으로 잘 해결해 나가시는 것을 보며 학습 능력이 대단한 분이라고 생각했습니다. 정말 고생 많으셨습니다!

> **김동혁**: 외부 API와의 통신을 맡아 예상치 못한 문제들이 생길 때마다, 깊은 고민과 빠른 행동으로 잘 처리하는 모습에서 문제에 대응하는 방법을 어깨 너머로 배울 수 있었습니다. 앞으로의 프로젝트에서는 더욱 더 많은 문제들이 발생할텐데, 그때도 우진님과 함께 잘 해결해가고 싶습니다!
>

> **김정모**: 이전 프로젝트에서 함께한 경험 덕분에 성향을 잘 알고 있었는데, 이번에도 역시 욕심 많게 여러 도메인을 가져갔습니다! 하지만 우진님의 실력을 알고 있어서 크게 걱정하지 않았고, 오히려 기대감이 더 컸습니다. 사실 질투심도 조금 있었습니다! (질투 1/4, 설렘 1/4, 기대 1/2) 심지어 제 질문이나 다른 조원들의 질문에도 하나하나 답변해 주면서도 자신의 개발을 멈추지 않고 진행하시는 모습은 정말 존경스럽고 대단하다는 생각이 들었습니다. 리스펙 합니다.
>

#### 김동혁
> **김시우**: 백엔드를 잘 하는 것은 이미 알고있었습니다. 하지만 프론트까지 잘하셔서 놀랐습니다. 양쪽 부분에서 궁금한 것이 있으면 언제든지 해결책을 알려주셔서 쉽고 빠르게 구현을 할 수 있었던 것 같습니다. 감사합니다!
> 

> **이효진**: 조근조근 기획부터 저희 조가 길을 잃을 때마다 집중할 수 있도록 길을 잡아주시느라 고생하셨습니다! 같은 비전공자인데도 개발을 너무 잘하셔서 이번에 많이 배울 수 있었습니다! 짧은 기간동안 고생해주셔서 감사합니다!!
> 

> **김서현**: 성격이 정말 꼼꼼하신 분입니다. 전체적인 프로젝트의 흐름을 잘 잡아주신 덕분에 막히는 부분이 생길 때마다 동혁님이 준비해주신 흐름을 따라가면서 해결할 수 있었습니다. 회의를 진행할 때도 특유의 집중력 덕분에 주제를 벗어나지 않고 토론을 할 수 있었고, 그 결과 프로젝트의 본질에 집중하여 개발을 진행하여 프로젝트의 완성도가 높아진 것 같습니다. 정말 고생 많으셨습니다!


> **이우진**: 항상 든든한 파트너. 3개월동안 같은 팀으로 서로 합을 맞춰보니 이젠 서로에게 도움 요청도 수월하게 하고 죽이 잘 맞는 팀워크를 보여준다고 생각한다. 파이널까지 함께 등을 믿고 맡길 수 있는 든든한 파트너!
>

> **김정모**:  동혁님과도 이전 프로젝트에서 호흡을 맞췄던 경험이 있어서, 그의 실력과 리더십을 잘 알고 있었습니다. 이번에도 역시 그 기대를 저버리지 않고 팀을 잘 이끌어주셨습니다. 회의나 토론 중에 논의가 조금 산으로 갈 때마다 다시 중심을 잡아주시고, 공식적인 조장은 아니지만 제 마음 속의 조장으로서 팀을 든든히 이끌어주셨죠. 이번 프로젝트에서는 도메인을 많이 가져가시진 않았지만, 마치 PM처럼 세부적인 부분보다는 전체적인 흐름을 보며 프로젝트를 진행하셨습니다. 존경합니다.
>

#### 김정모
> **김시우**: 리뷰와 비밀 리뷰를 담당하셨습니다. 무한 스크롤과 비밀리뷰 hover등 힘든 부분과 마지막날까지 이슈가 있었지만 해결하여 끝까지 완성시키셨습니다. 또한 문제점이 생길때 소통을 통하여 해결하려는 점이 정말 멋졌습니다. 파이널에도 기대하겠습니다! 
> 

> **이효진**: 저희 조에서 꼼꼼하게 디테일도 잡아주시고 기록도 항상 작성해주셨어요 감사합니다!! 마지막에 많은 이슈들로 힘든 일들이 있었지만 그래도 꿋꿋하게 마무리지으시는 모습 너무 대단하십니다. 어려워하시는 모습을 보이셨지만 그래도 결국엔 해내시는 모습! 너무 고생하셨습니다!
> 

> **김서현**: 같은 팀을 하기 전에도 항상 학원에 일찍 오시고 늦게 귀가하시는 모습을 보며 정말 성실한 분이라고 생각해왔고, 같은 팀을 하며 열심히 구현하는 모습에 감동을 받았습니다. 항상 배우려는 자세로 노력하시는 정모님을 보며 정말 크게 되실 분이라고 생각했습니다. 팀원들이 지칠 때도 장난스럽게 말을 걸어주셔서 팀의 분위기를 좋게 만들어주셨습니다. 개인적으로 배울 점이 많으신 분입니다. 고생하셨습니다.

> **이우진**: 리뷰와 비밀리뷰를 결국 끝까지 구현해낸 맏형님!
피그마 디자인부터 백, 프론트 모두 결국 자기 손으로 해내서 너무 든든하다. 이대로만 갑시다~
>

> **김동혁**: 백엔드에서의 로직과 프론트엔드에서의 화면 구성이 결코 단순하지 않은 리뷰 도메인을 맡아 끝까지 완성도를 위해 노력하는 모습에서 끈기를 배울 수 있었습니다. 긴 호흡의 최종 프로젝트에서도 지칠 때 마다 정모님을 보며 마음을 다잡고 함께 해낼 수 있으리라 생각합니다. 남은 일정들에서도 서로 도우며 나아가고 싶습니다.
> 
