<p align= "center">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=033d5e&height=300&section=header&text=PSMC&fontColor=f5f5f5&fontSize=90&fontAlignY=38&desc=Pro%20Sprots%20Medical%20Center&descAlignY=51" />
    </p>


## 프로젝트 배경

![스크린샷 2024-05-31 112315](https://github.com/semi-project-team/.github/assets/158137025/a110757c-bea9-4ae8-a288-9e285758627f)

    
## 🗣프로젝트 소개

![스크린샷 2024-05-31 112522](https://github.com/semi-project-team/.github/assets/158137025/6c5bb530-121e-4f12-9c61-bc42ae9bde5e)



## 팀 구성원 및 역할

<table align="center">
  <tr>
    <td>
      <a href="https://github.com/comaserious">
        <img src="https://avatars.githubusercontent.com/u/158137025?v=4" width="100" style="max-width: 100%;">
      </a>
    </td>
    <td>
      <a href="https://github.com/wjdals83">
          <img src="https://avatars.githubusercontent.com/u/138289674?v=4" width="100" style="max-width: 100%;">
      </a>
    </td>
    <td>
      <a href="https://github.com/Absensing">
        <img src="href="https://avatars.githubusercontent.com/u/158137158?v=4"" width="100" style="max-width: 100%;">
      </a>
    </td>
    <td>
      <a href="https://github.com/tmddbs9313">
          <img src="https://avatars.githubusercontent.com/u/127907841?v=4" width="100" style="max-width: 100%;">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/comaserious">이호준</a>
    </td>
    <td align="center">
      <a href="https://github.com/wjdals83">서정민</a>
    </td>
    <td align="center">
      <a href="https://github.com/Absensing">김재중</a>
    </td>
    <td align="center">
      <a href="https://github.com/tmddbs9313">조승윤</a>
    </td>
  </tr>
    <tr>
        <td align="center">팀장</td>
        <td align="center">Backend</td>
        <td align="center">Backend</td>
        <td align="center">Frontend</td>
    </tr>
</table>

## 1. ✔개발 환경
- Front : HTML/CSS, javaScript, Bootstrap, Thymeleaf
- Back : java/javaScript
- 버전 및 이슈 관리 : Github
- 협업 툴 : Notion
- 서비스 배포 환경 : jar

## 2. 브랜치 전략
 기능 별로 이름을 정하여 브랜치를 생성했습니다
 
- CSS : 뷰포트의 이미지를 생성하는 기능
- feature : CRUD 등 backend 관련 기능
- DB : db 업데이트
- bug : 기능에 오류 수정

브랜치 별로 커밋을 한 후 충돌이 발생하지 않거나 충돌을 해결한 후 master 브랜치에 merge 하는 방식을 채택했습니다

## 3. 프로젝트 구조

```
└─psmc
    ├─auth
    ├─common
    │  ├─exception
    │  └─model
    │      ├─dto
    │      └─method
    ├─configuration
    │  └─handler
    ├─mainPage
    ├─mediConnect
    ├─mypage
    ├─staff
    ├─theraLink
    └─user
```

충돌을 방지하기 위해서 기능 별로 역할을 분담하고 기능별로 패키지를 구성하였습니다
## 역할 분담

이호준
- 기능
  - 로그인, 아이디찾기, 비밀번호 찾기, 회원가입 약관, 회원가입 등록, 비밀번호 수정, mainpage 환자 등록, 스케쥴 작성, 식단표 작성, 스케쥴러 예약기능, theralink 블로그 생성 및 채팅 시스템
- DB
  - DB 테이블 생성

서정민
- UI
  - 페이지 : MediConnect
- 기능
   - MediConnect 생성하기 및 채팅 시스템, mainpage 의 MediConnect 최근 업데이트 정보
- DB
  - DB 테이블 생성

조승윤
- UI
  - 페이지 : 메인 페이지, mypage
- 기능
  - mypage 자신의 정보 수정

김재중
- UI
  - 페이지 : Staff
- 기능
    - staff 전공분야 또는 이름으로 의료진 또는 치료진 정보
- 오류 테스트

## 📅프로젝트 기간

<table>
    <tr>
        <th>전체 개발 기간</th>
        <td>2024.04.25 ~ 2024.06.02</td>
    </tr>
    <tr>
        <th>DB 작성</th>
        <td>2024.04.25 ~ 2024.05.02</td>
    </tr>
    <tr>
        <th>UI 구현</th>
        <td>2024.05.03 ~ 2024.05.23</td>
    </tr>
    <tr>
        <th>기능 구현</th>
        <td>2024.05.04 ~ 2024.05.30</td>
    </tr>
</table>

## 작업관리
1. [discussion 을 통해 팀 전체적으로 오늘 할 일을 정합니다](https://github.com/semi-project-team/PSMC/discussions?discussions_q=is%3Aopen+sort%3Adate_created)
2. [disscussion 을 통해 할당 받은 오늘의 과업에 대해 issue를 작성합니다](https://github.com/semi-project-team/PSMC/issues)
3. [기능을 완수하면 각각의 기능에 맞게 브랜치를 생성후 충돌을 모두 해결한 후 master 브랜치에 merge ](https://github.com/semi-project-team/PSMC/pulls?q=is%3Apr+is%3Aclosed)

## ERD

![asdadfasdfdsaf](https://github.com/semi-project-team/PSMC/assets/158137025/622cefcb-b247-41fd-8d21-5261461ce243)


## 기능 설명

### 1. 첫페이지

![1](https://github.com/semi-project-team/PSMC/assets/158137025/17b1888e-8225-40f8-96ae-afe6f1f3e492)

### 2. 회원 가입

![2](https://github.com/semi-project-team/PSMC/assets/158137025/66003d3e-d026-4e6c-998e-34ad6eeb4751)

![3](https://github.com/semi-project-team/PSMC/assets/158137025/193a7574-8f98-45bd-b347-74298fa2fe8c)

![4](https://github.com/semi-project-team/PSMC/assets/158137025/c16b8ea0-8585-49be-ae6b-3ffb0db18459)

### 3. 아이디 찾기 및 비밀번호 찾기

![11](https://github.com/semi-project-team/PSMC/assets/158137025/5dad0898-c879-4e98-b5e1-fe1d31c1315d)

![6](https://github.com/semi-project-team/PSMC/assets/158137025/5b87fa34-8d14-488e-9a77-94a065bfa0b3)

### 4. Mainpage

![12](https://github.com/semi-project-team/.github/assets/158137025/f09618d9-7325-4e5c-9a4e-580536ed91e4)

### 5. Mypage

![15](https://github.com/semi-project-team/.github/assets/158137025/2f03d9f3-2448-40e1-bf36-349a996567e8)

### 6. Scheduler

![13](https://github.com/semi-project-team/.github/assets/158137025/10de019a-3849-4109-8b42-13434ea3f43b)

### 7. MediConnect

![14](https://github.com/semi-project-team/.github/assets/158137025/6effaf04-43a0-4d19-8803-07345dc805da)

### 8. TheraLink

![16](https://github.com/semi-project-team/.github/assets/158137025/20cc701c-377e-4b53-b2e3-6516407074e0)

![17](https://github.com/semi-project-team/.github/assets/158137025/fabc292a-69e5-43df-8378-74bb9c7ca286)



### 9. Staff



- main page : 회원의 정보, 오늘의 식단표, 오늘의 스케쥴, mediconnect 과 theralink 의 최신 채팅 내용을 보여줍니다
  - 의료진의 경우 : 새로운 환자를 등록하여 새로운 프로젝트를 생성합니다, 또한 자신의 환자에 대해서 진료 예약을 할 수 있습니다
  - 재활 치료진의 경우 : 새로 부여받은 환자를 확인하고 재활 치료 시간을 예약할 수 있습니다
- scheduler : 해당 날짜 또는 사용자가 선택한 날짜를 기준으로 일요일부터 월요일까지의 전체 스케쥴을 보여줍니다. 또한 일정을 수정할 수 있습니다.
- mediconnect : 의료진에서 등록한 환자를 프로젝트 단위로 하여 프로젝트 하나당 하나의 공간을 생성하고 생성된 공간에서 할당된 재활 치료진과 의사소통을 할 수 있습니다
  - 의료진의 경우 : 현재 환자 상태에 대해서 소견을 작성하고 할당된 재활 치료사와 의사소통을 합니다. 또한 자신의 채팅을 삭제 및 프로젝트를 종료 할 수 있습니다
  - 재활 치료진의 경우 : 새로 부여 받은 환자에 대한 프로젝트를 확인할 수 있고 의료진의 소견을 확인하고 의견을 게시할 수 있고 또한 이에 근거하여 theralink를 생성하여 재활 치료에 관한 계획을 수립할 수 있습니다
- theralink : 할당된 환자에 따라 자동으로 프로젝트가 생성되고 그에 따라 각각의 소통 창구가 생성됩니다
  - 의료진의 경우 : 생성된 재활 일지를 확인하고 환자 상태에 대한 정보를 수집할 수 있고 또한 재활 치료진과 환자에 관하여 의사소통을 원할히 할 수 있습니다
  - 재활 치료진의 경우 : 할당된 환자에 따라 프로젝트가 생성 되고 이에 따라 재활 일지를 작성하고 자신의 소견을 작성 할 수 있습니다 작성된 소견에 대하여 의사와 의사소통을 할 수 있습니다
- staff : 기본적으로 각 분야에 해당하는 팀장 정보를 제공하여 의료 종사자 정보를 확인할 수 있습니다. 또한 전공 분야 또는 이름을 검색하여 해당 하는 의료전공자의 정보를 취득할 수 있습니다

## 신경 쓴 부분
- [예약 및 수정 시간 관련 방식](https://github.com/semi-project-team/PSMC/wiki/진료-시간-및-재활-치료시간-예약하기)
- [유사 채팅 생성](https://github.com/semi-project-team/PSMC/wiki/%EC%9C%A0%EC%82%AC-%EC%B1%84%ED%8C%85-%EA%B8%B0%EB%8A%A5-%EB%A7%8C%EB%93%A4%EA%B8%B0)
- [페이징 처리](https://github.com/semi-project-team/PSMC/wiki/Paging-%EC%B2%98%EB%A6%AC)
- [비밀번호찾기를 통한 이메일 전송](https://github.com/semi-project-team/PSMC/wiki/%EB%B9%84%EB%B0%80-%EB%B2%88%ED%98%B8-%EC%B0%BE%EA%B8%B0-%EA%B8%B0%EB%8A%A5)
- [이미지 저장](https://github.com/semi-project-team/PSMC/wiki/%EC%9D%B4%EB%AF%B8%EC%A7%80-%EC%A0%80%EC%9E%A5%ED%95%98%EA%B8%B0)
