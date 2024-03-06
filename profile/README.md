## 📅 프로젝트 일정

- Project Conception & Initiation : 20240215~202403

### 🧑🏻 프로젝트 멤버

<table>
 <tr>
    <td align="center"><a href="https://github.com/seunghyun0522"><img src="https://avatars.githubusercontent.com/seunghyun0522" width="130px;""></a></td>
    <td align="center"><a href="https://github.com/gywls20"><img src="https://avatars.githubusercontent.com/gywls20" width="130px;""></a></td>
    <td align="center"><a href="https://github.com/whgek506"><img src="https://avatars.githubusercontent.com/whgek506" width="130px;""></a></td>
    <td align="center"><a href="https://github.com/gyuchanlee"><img src="https://avatars.githubusercontent.com/gyuchanlee" width="130px;""></a></td>
    <td align="center"><a href="https://github.com/Tofubeen"><img src="https://avatars.githubusercontent.com/Tofubeen" width="130px;""></a></td>
    <td align="center"><a href="https://github.com/jgkwon3"><img src="https://avatars.githubusercontent.com/jgkwon3" width="130px;""></a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/seunghyun0522"><b>seunghyun0522</b></a></td>
    <td align="center"><a href="https://github.com/gywls20"><b>gywls20</b></a></td>
    <td align="center"><a href="https://github.com/whgek506"><b>whgek506</b></a></td>
    <td align="center"><a href="https://github.com/gyuchanlee"><b>gyuchanlee</b></a></td>
    <td align="center"><a href="https://github.com/Tofubeen"><b>Tofubeen</b></a></td>
    <td align="center"><a href="https://github.com/jgkwon3"><b>jgkwon3</b></a></td>

  </tr>

</table>


</br>

# Project Conception & Initiation

### ✏️ Contents

-   기획 주제
-   Stack & tool
-   아이디어 스피치
-   요구 사항 정의서 
-   user flow
-   DB
-   UI 설계

_목차의 순서로 기획_
## 기획 주제 선정 (20240215~202403)

<p align="center">
<img src="https://github.com/I-on-I/.github/assets/75532258/fa71ce59-7cfb-426d-b470-052f3593b856" width="300" >
</p>

 
**프로젝트 주제**: 개인 서재와 책 추천 공유 플랫폼

**팀명**: IF (mbti I와 F의 모임)

**서비스**: e-book service(e-book 구현), 책 등록 및 관리, 책 리뷰 공유, (+e-book 음성지원)


## Stack & Tool (추후에 변경)

### 프론트엔드
- React JS
- styled-component
- react-query
- recoil
- js
- axios

### UI
- Figma
- excalidraw

### 백엔드
- Java17
- Spring Boot
- MySQL8
- Gradle
- JPA
- Mybatis
- 시큐리티
- 쿼리DS
- 타임리프

### 데브옵스
- NCP
- Docker
- Jenkins

### 커뮤니케이션
- Notion
- Google Sheet
- Figma



## 아이디어 스피치(20240215 ~ 202403)

우리 팀 IF는 책을 사랑하는 개인들을 위한 플랫폼을 만들기 위해 모였습니다. 이 플랫폼은 사용자들이 개인 서재를 관리하고, 읽은 책에 대한 리뷰를 공유하며, 서로에게 책을 추천하는 공간입니다. 우리는 책을 통해 각자의 성장과 경험을 나누고, 동시에 새로운 책을 발견하는 즐거움을 함께 나누고 싶습니다. 따라서 이 플랫폼은 개인의 취향과 관심사를 반영한 책 추천 기능을 중심으로 구성될 것입니다.

브레인스토밍과 아이디어 스피치는 Excalidraw Tool을 이용하여 진행했습니다. 플랫폼의 주요 기능과 요소들에 대한 고민과 토론을 통해 개발 초기부터 팀원들 간에 확고한 이해와 합의를 이끌어냈습니다. 이를 바탕으로 요구사항 정의서를 작성하고 프로젝트의 전반적인 흐름을 파악하는 USE FLOW를 작성하였습니다.

필요한 기능과 비기능적인 요소들은 요구사항명세서와 DB 설계할 때 디테일하게 접근하였습니다. 이를 통해 각 기능이 어떻게 동작해야 하는지 명확하게 이해하고, 개발 과정에서 오류와 불일치를 최소화하고자 노력했습니다.

<p align="center">
<img src="https://github.com/I-on-I/.github/assets/75532258/9d431fdc-b4c6-406c-bf33-379804747508" width="300">
</p>

필요한 기능과 비기능적인 요소들은 요구사항명세서와 DB 설계할 때 디테일하게 접근




## 요구 사항 정의서 작성 (20240215 ~ 202403)

우리의 플랫폼은 사용자가 개인 서재를 관리하고, 책에 대한 리뷰를 작성하며, 다른 사용자와 책을 공유하고자 하는 요구사항을 충족시켜야 합니다. 이를 위해 우리는 사용자 관리, 서재 관리, 책 등록 및 관리, 책 추천, 리뷰 작성과 공유, 그리고 추가적인 기능으로 구성된 요구사항 정의서를 작성했습니다. 이 정의서를 바탕으로 프로젝트를 개발하고, 변경사항이 생길 때마다 업데이트할 예정입니다.

<p align="center">
<img src="https://github.com/I-on-I/.github/assets/75532258/105de1f9-2406-4a0b-9469-b92c46664941" width="500">
</p>


## USE FLOW 작성(20240215 ~ 202403)

플랫폼의 전반적인 흐름을 파악하고, 각 기능의 사용자 행동과 시스템의 반응을 명확하게 이해하기 위해 USE FLOW를 작성했습니다. 이를 통해 개발 과정에서 사용자 경험을 최적화하고, 팀원들 간의 의사소통을 원활하게 할 수 있었습니다.


<p align="center">
<img src="https://github.com/I-on-I/.github/assets/75532258/920d82fa-552c-4510-a337-06c60c81c213" width="500">
</p>

## DB 작성(20240215 ~ 202403)

USE FLOW와 요구사항 정의서를 바탕으로 DB 테이블 ERD를 작성하였습니다. 각 테이블은 사용자, 책, 리뷰 등과 같은 핵심 엔터티를 포함하여 플랫폼의 핵심 기능을 지원하도록 구성되었습니다.


<p align="center">
<img src="https://github.com/I-on-I/.github/assets/75532258/921cfacc-4403-4c92-a9c3-3396f20fc8e5" width="500">
</p>



## UI 설계

플랫폼의 UI 설계는 Figma를 사용하여 진행하였습니다. 이를 통해 개발 초기부터 사용자 경험을 고려한 디자인을 구상하고, 팀원들 간의 의견을 적극 수렴하여 최종적인 디자인을 결정했습니다. 
[Figma 링크](https://www.figma.com/file/NDXn1v6CLkbVsGQ35dnLZp/Untitled?type=design&node-id=0-1&mode=design&t=CrR5XDJOEUBoYCOG-0)


<p align="center">
<img src="https://github.com/I-on-I/.github/assets/75532258/dfa4ddb2-638e-4589-9ddb-b5987fb49b33" width="500">
</p>
