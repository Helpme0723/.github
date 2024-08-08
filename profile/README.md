# 최종 프로젝트 사용자 창작물 플랫폼

<img src="https://github.com/user-attachments/assets/c9ce2feb-8b0e-42eb-ba95-0e16eec610cb" alt="favicon" width="300" height="300">

## TalentVerse
- [배포 웹 사이트 링크]() -경로 추가필요
- [API 명세서링크](https://teamsparta.notion.site/079afbd71f7e47da9bbd2c45b85a0151)
- [ERD 링크]() - 경로 추가필요
- [시연 영상 링크]() -경로 추가필요



### 프로젝트 소개
- 사용자들이 자신의 창작물을 업로드하고, 해당 컨텐츠를 무료 혹은 구매하여 볼 수 있는 서비스입니다.


### 📌 주요 기능

<details>
  <summary>1. 인증</summary>
  <div markdown="1">
    <ul>
      <li>회원가입 : 사용자는 이메일과 패스워드, 사용자 이름을 입력하여 회원가입 할 수 있습니다.</li>
      <li> 로그인 : 회원가입에 성공한 사용자는 이메일과 패스워드를 통하여 로그인 할 수 있습니다.</li>
      <li>로그아웃 : 로그인한 사용자의 리프레쉬 토큰이 삭제됩니다.</li>
      <li>토큰 재발급 : 만료된 액세스 토큰을 리프레쉬 토큰을 사용하여 재발급합니다.</li>
      <li>이메일 중복 조회 : 회원가입시 이미 있는 이메일이 있는지 체크 할 수 있습니다.</li>
      <li>비밀번호 찾기 : 사용자가 비밀번호를 잃어버리면 찾을 수 있습니다.</li>
      <li>회원탈퇴 : 로그인한 사용자의 정보가 삭제됩니다.</li>
    </ul>
  </div>
</details>

<details>
  <summary>2. 내 정보 관리</summary>
  <div markdown="2">
    <ul>
      <li>내 정보 조회 : 로그인한 사용자는 본인의 정보를 조회할 수 있습니다.</li>
      <li>내 정보 수정 : 로그인한 사용자는 본인의 이름, 자기소개 등을 수정할 수 있습니다.</li>
      <li>타 유저 정보 조회 : 로그인한 사용자는 타인의 정보를 조회할 수 있습니다.</li>
      <li>비밀번호 수정 : 로그인한 사용자는 본인의 비밀번호를 변경할 수 있습니다.</li>
      <li>불호 태그 추가 : 로그인한 사용자는 본인이 싫어하는 태그를 추가 할 수 있습니다.</li>
      <li>불호 태그 삭제 : 로그인한 사용자는 본인이 추가한 태그를 삭제 할 수있습니다. </li>
      <li>알림 설정 : 로그인한 사용자는 본인이 받고싶은 알림을 설정할 수 있습니다.</li>
    </ul>
  </div>
</details>

<details>
  <summary>3. 채널</summary>
  <div markdown="3">
    <ul>
      <li>채널 생성 : 로그인한 사용자는 본인의 채널을 여러개 만들 수 있습니다.</li>
      <li>내 채널 전체 조회 : 사용자가 만든 모든 채널의 목록을 조회 할 수 있습니다.</li>
      <li>타 유저 채널 전체 조회 : 사용자는 다른 유저의 채널을 볼 수 있습니다.</li>
      <li>채널 상세 조회 : 사용자가 만든 채널의 세부정보를 볼 수 있습니다.</li>
      <li>채널 정보 수정 : 사용자가 만든 채널의 세부정보를 수정 할 수 있습니다.</li>
      <li>채널 정보 삭제 : 사용자가 만든 채널을 삭제 할 수 있습니다.</li>
      <li>내 채널 통계 조회 : 사용자가 만든 채널의 일간 통계, 월간 통계를 조회 할 수 있습니다.</li>
    </ul>
  </div>
</details>

<details>
  <summary>4. 시리즈</summary>
  <div markdown="4">
    <ul>
      <li>시리즈 생성 : 로그인한 사용자는 포스트를 넣을 시리즈를 만들 수 있습니다.</li>
      <li>시리즈 조회 : 로그인한 사용자는 본인이 만든 시리즈를 조회 할 수 있습니다.</li>
      <li>시리즈 상세 조회 : 사용자는 본인이 만든 시리즈의 세부정보를 조회 할 수 있습니다.</li>
      <li>시리즈 정보 수정 : 사용자는 본인이 만든 시리즈의 세부정보를 수정 할 수 있습니다.</li>
      <li>시리즈 삭제 : 사용자는 본인이 만든 시리즈를 삭제 할 수 있습니다.</li>
    </ul>
  </div>
</details>

<details>
  <summary>5. 포스트</summary>
  <div markdown="5">
    <ul>
      <li>포스트 작성 : 로그인한 사용자는 본인의 창작물을 유/무료로 업로드 할 수 있습니다. </li>
      <li>전체 포스트 조회 : 사용자는 메인페이지의 업로드된 창작물들을 볼 수 있습니다.</li>
      <li>포스트 상세조회 : 로그인한 사용자는 창작물들을 열람 할 수 있습니다.</li>
      <li>포스트 수정 : 로그인한 사용자는 본인이 만든 포스트를 수정 할 수 있습니다. </li>
      <li>포스트 삭제 : 로그인한 사용자는 본인의 포스트를 삭제 할 수 있습니다. </li>
      <li>포스트 좋아요 등록 : 로그인한 사용자는 다른 유저의 포스트에 좋아요를 누를 수 있습니다.</li>
      <li>포스트 좋아요 취소 : 로그인한 사용자는 눌렀던 다른 유저의 포스트에 좋아요를 취소 할 수 있습니다.</li>
    </ul>
  </div>
</details>

<details>
  <summary>6. 댓글</summary>
  <div markdown="6">
    <ul>
      <li>댓글 생성 : 로그인한 사용자는 모든 포스트에 댓글을 달 수 있습니다.</li>
      <li>댓글 수정 : 로그인한 사용자는 본인의 댓글을 수정 할 수 있습니다.</li>
      <li>댓글 삭제 : 로그인한 사용자는 본인의 댓글을 삭제 할 수 있습니다.</li>
      <li>댓글 좋아요 등록 : 로그인한 사용자는 다른 사용자의 댓글에 좋아요를 누를 수 있습니다.</li>
      <li>댓글 좋아요 취소 : 로그인한 사용자는 다른 사용자의 눌렀던 좋아요를 취소 할 수 있습니다.</li>
    </ul>
  </div>
</details>

<details>
  <summary>7. 구독</summary>
  <div markdown="7">
    <ul>
      <li>채널 구독 : 로그인한 사용자는 다른 사람의 채널을 구독 할 수 있습니다.</li>
      <li>채널 구독 취소 : 로그인한 사용자는 구독한 채널들을 취소를 할 수 있습니다.</li>
      <li>내 구독 목록 조회 : 본인이 구독한 채널들을 조회 할 수 있습니다.</li>
      <li>내 구독 채널의 포스트 목록 조회 : 본인이 구독한 채널의 포스트 목록을 조회 할 수 있습니다. </li>
    </ul>
  </div>
</details>

<details>
  <summary>8. 라이브러리</summary>
  <div markdown="8">
    <ul>
      <li>좋아요한 포스트 조회 : 로그인한 사용자는 본인이 누른 포스트를 조회 할 수 있습니다.</li>
      <li>내가 쓴 댓글 조회 : 로그인한 사용자는 본인이 쓴 댓글을 조회 할 수 있습니다.</li>
      <li>구매한 포스트 조회 : 로그인한 사용자는 본인이 구매한 포스트들을 조회 할 수 있습니다.</li>
    </ul>
  </div>
</details>

<details>
  <summary>9. 구매</summary>
  <div markdown="9">
    <ul>
      <li>포스트 구매 : 로그인한 사용자는 본인이 가지고 있는 포인트로 포스트를 구매 할 수 있습니다.</li>
    </ul>
  </div>
</details>

<details>
  <summary>10. 포인트</summary>
  <div markdown="10">
    <ul>
      <li>포인트 충전 : 로그인한 사용자는 결제 시스템을 통해 포인트를 충전할 수 있습니다.</li>
       <li>포인트 증감 내역 조회 : 로그인한 사용자는 본인의 포인트 증감 내역을 확인 할 수 있습니다.</li>
    </ul>
  </div>
</details>

<details>
  <summary>11. 알림</summary>
  <div markdown="11">
    <ul>
       <li>알림 목록 조회 : 로그인한 사용자는 본인이 설정한 알림들을 볼수 있습니다.</li>
    </ul>
  </div>
</details>

<details>
  <summary>12. 신고</summary>
  <div markdown="12">
    <ul>
       <li>포스트 신고 : 로그인한 사용자는 부적절한 포스트를 신고 할 수 있습니다.</li>
       <li>댓글 신고 : 로그인한 사용자는 부적절한 댓글을 신고 할 수 있습니다.</li>
    </ul>
  </div>
</details>

### 프로젝트 설치 및 실행 방법 (with npm)

#### 1. 프로젝트 clone(배포링크가 있어서 일단 어캐할지 몰라 냅뒀어요)







## 📜 프로젝트 기획 및 설계

### [Code Convention](https://teamsparta.notion.site/Code-Convention-34099cda765f4e9594f657821c5437a6)

### Github Rules

| 작업 타입   | 작업 내용                                |
| ----------- | ---------------------------------------- |
| ✨ Update   | 해당 파일에 새로운 기능이 생김           |
| 🎉 Feat     | 없던 파일을 생성함, 초기 세팅, 기능 구현 |
| 🐛 Bugfix   | 버그 수정                                |
| ♻️ Refactor | 코드 리팩토링                            |
| 🩹 Fix      | 코드 수정                                |

## 📌 기술 스택

### Environment

![Git](https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Github](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Vscode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

### Development

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)
![AMAZON EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge&logo=Amazon%20EC2&logoColor=white)
![AMAZON RDS](https://img.shields.io/badge/amazonrds-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white)
![AMAZON S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![ElasticSearch](https://img.shields.io/badge/-ElasticSearch-005571?style=for-the-badge&logo=elasticsearch)

### Communication

![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)


## 👨‍👨‍👦‍👦 프로젝트 제작 인원

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/CMINSOO"><img src="https://avatars.githubusercontent.com/u/165575863?v=4" width="100px;" alt="조민수"/><br /><sub><b> 리더 : 조민수 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/ysys29"><img src="https://avatars.githubusercontent.com/u/167045109?v=4" width="100px;" alt="이연서"/><br /><sub><b> 부리더 : 이연서 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/NohSiHeon"><img src="https://avatars.githubusercontent.com/u/91312161?v=4" width="100px;" alt="노시헌"/><br /><sub><b> 팀원 : 노시헌 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/gus11als"><img src="https://avatars.githubusercontent.com/u/102670376?v=4" width="100px;" alt="김현민"/><br /><sub><b> 팀원 : 김현민 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/devJaem"><img src="https://avatars.githubusercontent.com/u/125876896?v=4" width="100px;" alt="정재민"/><br /><sub><b> 팀원 : 정재민 </b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

