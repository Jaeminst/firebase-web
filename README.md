# firebase-web
firebase를 활용한 backendless 프론트엔드 웹

![스크린샷, 2022-06-17 00-07-14](https://user-images.githubusercontent.com/99124279/174101246-afb55513-06a7-47a3-8958-486ec5d228f4.png)


## Getting Started with firebase app
1. [Firebase에서 App 생성을 가이드를 참고하여 시작 합니다.](https://firebase.google.com/docs/web/setup#create-firebase-project-and-app)
2. Authentication에서 시작하기를 누른후 로그인 제공업체에 `이메일/비밀번호`를 추가합니다. 
3. Firestore Database에서 시작하기를 누른후 `products` collection을 생성합니다.
   * 위치: asia-northeast3
4. Storage에서 시작하기를 눌러줍니다.
5. 프로젝트 설정에서 내 앱 `</>`버튼을 누릅니다.

![스크린샷, 2022-06-16 23-36-26](https://user-images.githubusercontent.com/99124279/174095747-572434f7-eef9-42c0-8de5-1b54a1bdedcb.png)

![스크린샷, 2022-06-16 23-37-170](https://user-images.githubusercontent.com/99124279/174095618-c62db848-4396-4084-a957-916c950f798b.png)


## Clone Repository

```bash
$ git clone git@github.com:Jaeminst/firebase-web.git
$ cd firebase-web
```

## config.js
아래와 같이 파일을 생성후 위 단계에서 생성한 앱의 `firebaseConfig`를 삽입합니다.

![스크린샷, 2022-06-16 23-34-23](https://user-images.githubusercontent.com/99124279/174093984-bac66aef-f320-48a4-8230-cfef260516c5.png)

## Firebase Serve Testing on local

```bash
$ npm install -g firebase-tools@9.23.1
$ firebase login
$ firebase serve

=== Serving from '---'...

i  hosting: Serving hosting files from: public,src
✔  hosting: Local server: http://localhost:5000
```

## 웹 동작 설명
![스크린샷, 2022-06-16 23-50-42](https://user-images.githubusercontent.com/99124279/174098814-565ab1cb-0500-47ba-803a-0f774f3def58.png)


### 회원가입 > 로그인 > 상품등록 > 로그아웃

### 회원가입

![스크린샷, 2022-06-16 23-50-54](https://user-images.githubusercontent.com/99124279/174098646-6ffada57-154a-4a30-a706-26660550e5bb.png) 을 누르고 이름, 이메일, 비밀번호(6자 이상)을 입력후 가입합니다.

![스크린샷, 2022-06-16 23-52-09](https://user-images.githubusercontent.com/99124279/174099090-dfb28f38-04fd-4ea6-a886-bab9914f5b9e.png)

가입이 완료되면 자동으로 로그인 페이지로 이동됩니다.

### 로그인

![스크린샷, 2022-06-16 23-52-28](https://user-images.githubusercontent.com/99124279/174099199-f5c60540-d8a1-467a-b273-eaa3b7e85216.png) 가입시 입력했던 이메일과 비밀번호를 입력 후 로그인합니다.

![스크린샷, 2022-06-16 23-52-41](https://user-images.githubusercontent.com/99124279/174099340-2f9d0b7e-19da-4bcc-9acd-708aaf6ba34c.png)

### 상품 등록

![스크린샷, 2022-06-16 23-52-52](https://user-images.githubusercontent.com/99124279/174099548-8f9c3c41-0ea7-45a8-aa83-c9fbb6e1a704.png) 원하는 상품을 등록할 수 있습니다.

![스크린샷, 2022-06-16 23-53-48](https://user-images.githubusercontent.com/99124279/174099585-b7520374-a357-47ca-a478-b6f995e28f77.png)

![스크린샷, 2022-06-16 23-54-11](https://user-images.githubusercontent.com/99124279/174099846-56f357bf-f2d8-4ce0-93f7-593e4e9d04a7.png)

### 로그아웃

![스크린샷, 2022-06-17 00-01-59](https://user-images.githubusercontent.com/99124279/174100223-190f0ce1-fec1-479e-b5fd-d5e15022bd11.png)


![스크린샷, 2022-06-16 23-54-26](https://user-images.githubusercontent.com/99124279/174100139-52e8f7e4-83f3-4550-b2c2-7154eb6bd246.png)을 누르면 다시 로그인과 회원가입 NavBar가 활성화 됩니다.

![스크린샷, 2022-06-16 23-50-42](https://user-images.githubusercontent.com/99124279/174098814-565ab1cb-0500-47ba-803a-0f774f3def58.png)
