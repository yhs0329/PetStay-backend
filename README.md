
# 👨‍👩‍👦‍👦 Pet Stay 👨‍👩‍👦‍👦 

[![license](https://img.shields.io/badge/License-AGPL-red)](https://github.com/NDjust/Generate-HeadLine/blob/master/LICENSE)
[![code](https://img.shields.io/badge/Code-Python3.7-blue)](https://docs.python.org/3/license.html)
[![data](https://img.shields.io/badge/Data-news-blueviolet)](https://news.chosun.com/ranking/list.html)
[![member](https://img.shields.io/badge/Project-Member-brightgreen)](https://github.com/NDjust/Generate-HeadLine/blob/Feature_README/README.md#participation-member)
[![DBMS](https://img.shields.io/badge/DBMS-MySQL-orange)](https://www.mysql.com/downloads/)

(↑관련된 뱃지 달기)

> ### 반려인과 펫시터를 연결시켜주는 중개 사이트 👉 https://rollingpaper.site/

(↑프로젝트 한 줄 설명 : 설명을 장황하게 작성하는 것보다 한 줄로 어떤 프로젝트인지 설명하는 것이 훨씬 직관적이다.)

![image](https://github.com/HJ17J/PetStay-backend/assets/154948606/1a19b76e-2e17-497e-bf9c-01daef8c482d)


(↑프로젝트를 대표하는 대표 이미지)


## 📖 Description

오프라인에 존재했던 롤링페이퍼 서비스를 온라인으로 옮겨왔습니다.

친구들, 동료들과 함께 링크를 공유하여 한 사람을 위한 롤링페이퍼를 만들어보세요.

다양한 종류의 편지지와 스티커로 화면을 꾸미고, 소중한 사람에게 뜻깊은 경험을 선물하세요!

(↑프로젝트에 대한 자세한 설명)

## :baby_chick: Demo
(↑해당 프로젝트가 실제 배포되고 있지 않아서, 이미지로 프로젝트의 뷰를 대체할 경우)
<p float="left">
    <img src="https://lh3.googleusercontent.com/iYHEwh2_Q6nIKS67eItV4AwIokeJDNe0ojtpWGqKpRyhaRlmCSmBcnkFNCmXbTkajKA=w2560-h1330-rw" width=200 />
    <img src="https://lh3.googleusercontent.com/xl0sqT6Jz1p9Gq9slw4VXRr-akf4v74b_k3QkZUMZPvYV37-e5LqTZcOjofof4Xyl48=w2560-h1330-rw" width=200 />
    <img src="https://lh3.googleusercontent.com/JqUUXWSgU0bhSBpOObERLvfUGE3eBnInmYvDMY3S2aAatyeFKLOifWnBLgZ0KLGbmA=w2560-h1330-rw" width=200 />
    <img src="https://lh3.googleusercontent.com/AdN5fkguQMSc4M6iVkAFONsuxZhOQaKE7TDzuhF56FgDLORAnBv8160W7vva4a6kFBg=w2560-h1330-rw" width=200 />
    <img src="https://lh3.googleusercontent.com/ruDvvtKehqGB_4PX7QBsUY2RLDe_v6g5FL-_XmC6SUGjKUQqa08Uy-DtsNi8wYuuXU4=w2560-h1330-rw" width=200 />
</p>

## ⭐ Main Feature
### 예약 관리 기능
- react-calendar를 사용하여 예약 일정 선택 기능 구현
- sequelize로 db저장

### 회원가입 및 로그인 
- session-express 사용

### 채팅방 기능
- socekt.io를 사용하여 실시간 채팅 구현
- aws의 s3를 사용하여 이미지 저장 및 경로를 소켓으로 전송할 수 있도록 구현

## 💻 Getting Started

### Installation
```
npm install
```
### Develop Mode
```
npm run dev
```
### Production
```
npm start
```

## 🔧 Stack
- **Language**: JavaScript
- **Library & Framework** : Node.js
- **Database** : AWS RDS (Mysql)
- **ORM** : Sequelize
- **Deploy**: AWS EC2

## :open_file_folder: Project Structure

```markdown
frontend
├── public
│   ├── images
├── src
    ├── components
    └── config
    └── locales
    └── pages
    └── store
    └── styles
    └── types
├── App.tsx
├── index.tsx
backend
├── config
├── controller
├── models
├── routes
├── sockets
├── app.js
```

## 🔨 Server Architecture
(↑서버 아키텍처에 대한 내용을 그림으로 표현함으로써 인프라를 어떻게 구축했는 지 한 눈에 보여줄 수 있다.)
![](https://docs.aws.amazon.com/gamelift/latest/developerguide/images/realtime-whatis-architecture-vsd.png)

## ⚒ CI/CD
- github actions를 활용해서 지속적 통합 및 배포
- `feature` 브랜치에서 `dev`로 Pull Request를 보내면, CI가 동작된다.
- `dev`에서 `master`로 Pull Request를 보내면, CI가 동작되고 Merge가 되면, 운영 리소스에 배포된다.

## 👨‍💻 Role & Contribution

**Frontend (Web)**

- 관리자 페이지 (Vue.js) 개발
- 전체 아키텍처 구성

**Devops**

- CI/CD 구축 (Docker, Github Action)
- 서버 모니터링

**etc**

- 전체 개발 일정 및 이슈 관리

## 👨‍👩‍👧‍👦 Developer
*  **박재성** ([jaeseongDev](https://github.com/jaeseongDev))
*  **고성진** ([seongjin96](https://github.com/seongjin96))
*  **조연희** ([yeoneei](https://github.com/yeoneei))
