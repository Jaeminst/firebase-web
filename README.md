# firebase-web
firebase를 활용한 프론트엔드 웹

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
