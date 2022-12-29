# 인력부족 / Stady
## 목차  
[1.프로젝트 개요](#프로젝트-개요)  
[2.팀 소개](#팀-소개)  
[3.사용 기술](#사용-기술)  
[4.프로젝트 진행 과정](#프로젝트-진행-과정)  
[5.프로젝트 상세 소개](#프로젝트-상세-소개)  
[6.사용자 수행 흐름도](#사용자-수행-흐름도)  
[7.프로젝트 추진 결과](#프로젝트-추진-결과)  
[8.결과 및 발표 자료](#결과-및-발표-자료)
<hr>  

## 프로젝트 개요
### 프로젝트 주제
STADY는 기존 시장에 나와있는 모든 스터디플래너의 장점만 모아 만든 앱입니다  

### 프로젝트 동기
시중에 나와있는 플래너 어플리케이션을 사용하면서 친구들과 플래너를 공유하며 사용하고 싶었지만 해당 기능을 가진 앱을 찾을 수 없었음

### 수행 목표
앱을 사용하여 실시간으로 플래너 공유가 가능하도록 함

## 팀 소개
<table>
  <tr>
    <td> <img src="https://media.discordapp.net/attachments/1019754746300608562/1057937464511189072/image.png"  alt="1" width = 110px height = 110px ></td>
    <td><img src="https://media.discordapp.net/attachments/1019754746300608562/1057936834212147250/image.png" alt="2" width = 110px height = 110px></td>
    <td><img src="https://media.discordapp.net/attachments/1019754746300608562/1057936961630912603/image.png" alt="3" width = 110px height = 110px></td>
   </tr>
   <tr>
    <td>팀장: <strong>임태현</strong></td>
    <td>팀원: <strong>박찬현</strong></td>
    <td>팀원: <strong>박민준</strong></td>
  </tr>
  <tr>
    <td><a href="https://github.com/noeulnight">Github</a></td>
    <td><a href="https://github.com/Hanavi999">Github</a></td>
    <td><a href="https://github.com/pmj0815">Github</a></td>
  </tr>
  <tr>
    <td><a href="mailto:contact@limtaehyun.dev">Email</a></td>
    <td><a href="mailto:chanhyeon777@gmail.com">Email</a></td>
    <td><a href="mailto:pmj081514@gmail.com">Email</a></td>
  </tr>
</table>

## 사용 기술
<table>
  <tr>
    <td><img src="https://yt3.ggpht.com/ytc/AMLnZu_xIo0iBEJrOw_Nk6ZGjlOaKmnk4lx6lZAfMxTLZg=s900-c-k-c0x00ffffff-no-rj" alt="alt" width=50px height=50px /></td>
    <td><strong>Mariadb</strong><br/>기본적인 유저 정보 및 플래너 정보 저장용 관계형 DB</td>
  </tr>
  <tr>
    <td><img src="https://miro.medium.com/max/512/1*doAg1_fMQKWFoub-6gwUiQ.png" alt="alt" width=50px height=50px /></td>
    <td><strong>Mongodb</strong><br/>실시간으로 저장되는 채팅정보를 저장할 비관계형 DB</td>
  </tr>
  <tr>
    <td><img src="https://the-guild.dev/blog-assets/nodejs-esm/nodejs_logo.png" alt="alt" width=50px height=50px /></td>
    <td><strong>Node.js</strong><br/>리엑트와 백엔드 서버에서 사용하기 위한 언어</td>
  </tr>
  <tr>
    <td><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1200px-React-icon.svg.png" alt="alt" width=50px height=50px /></td>
    <td><strong>React.js</strong><br/>프론트엔드 프레임워크</td>
  </tr>
  <tr>
    <td><img src="https://static-00.iconduck.com/assets.00/nestjs-icon-512x510-9nvpcyc3.png" alt="alt" width=50px height=50px /></td>
    <td><strong>Nest.js</strong><br/>백엔드 프레임워크</td>
  </tr>
</table>

## 프로젝트 진행 과정
<table>
  <tr>
    <th>월</th>
    <th>진행내역</th>
  </tr>
  <tr>
    <td>8월</td>
    <td>프로젝트 구상 및 실현 가능성 확인 & 계획서 작성</td>
  </tr>
  <tr>
    <td>9월 초</td>
    <td>데이터베이스 구상 & 프론트엔드 디자인</td>
  </tr>
  <tr>
    <td>9월 중반</td>
    <td>프로젝트 계획서 1차 발표</td>
  </tr>
  <tr>
    <td>9월 말</td>
    <td>데이터베이스 구현 & 백엔드 개발 시작</td>
  </tr>
  <tr>
    <td>10월</td>
    <td>프론트엔드 디자인 마감 & 프론트엔드 개발 시작</td>
  </tr>
  <tr>
    <td>11월</td>
    <td>프로젝트 계속 진행</td>
  </tr>
  <tr>
    <td>12월 초</td>
    <td>백엔드 완료</td>
  </tr>
  <tr>
    <td>12월 중반</td>
    <td>프론트엔드 완료</td>
  </tr>
</table>

## 프로젝트 상세 소개
### 레이아웃 세부 설명
[Figma](https://www.figma.com/file/5Pa3EX3ZegYCBas3gSlTIs/%EC%9D%B8%EB%A0%A5%EB%B6%80%EC%A1%B1?node-id=0%3A1&t=pltwfYQfP5MeXGkg-1)
### 데이터베이스 ERD
![ERD](https://media.discordapp.net/attachments/1019754746300608562/1057943237857378344/image.png?width=2074&height=1366)
[ERDCloud에서 확인하기](https://www.erdcloud.com/d/bREiRTmcQXGNKBAxg)



## 사용자 수행 흐름도
[Figma](https://www.figma.com/file/5Pa3EX3ZegYCBas3gSlTIs/%EC%9D%B8%EB%A0%A5%EB%B6%80%EC%A1%B1?node-id=0%3A1&t=pltwfYQfP5MeXGkg-1)

## 프로젝트 추진 결과
### 결과 분석
프로젝트를 진행하면서 시간이 부족하여 완성하지 못한 부분이 많지만 프로젝트를 진행하며 막히는 사항은 없었음
### 유지 보수
유지보수가 쉽도록 VCS(Github)를 사용함

## 결과 및 발표 자료
[Github](https://github.com/manpowershortage)  
[실행 주소](https://stady.gbsw.hs.kr)  
[프로젝트 소개 영상]()  
[계획 발표 자료](https://docs.google.com/presentation/d/1-7bKsCSt0vc6CL8CcKAIaILbA2262-Zv/edit?usp=sharing&ouid=105433774271668253882&rtpof=true&sd=true)  
[중간 발표 자료](https://docs.google.com/presentation/d/1-2EKw7hU9zCuHC86R-VUhtwdn66SFOi2/edit?usp=sharing&ouid=105433774271668253882&rtpof=true&sd=true)  
[최종 발표 자료]()