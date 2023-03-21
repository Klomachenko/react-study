# React-Study

---

### React를 공부해야 하는 이유

- 프론트엔드 개발자와 퍼블리셔를 나누는 큰 기준 중 하나
    - 자바스크립트의 라이브러리와 프레임워크를 사용하는 것
- Naver Vibe, Instagram 등 웹사이트등 SPA(Single Page Application)를 구현하기 위함
    - html 파일을 1개만 쓰고
    - 다른 페이지를 보여주고 싶을 때 html 부분만 교체해 보여줌
- Vanilla JS를 이용할 때 코드가 길어지는 것을 방지하기 위함
- 큰 프로젝트일수록 html을 함수, array, object등에 보관하고 재사용할 수 있어 html 관리가 편해짐
- React Native를 쓰면 같은 React 문법으로 모바일 앱개발도 가능함

### 스터디 설명

- 관리 및 재사용에 용이하고, SPA 구현을 가능하게 해주는 React를 공부하기 위함
- Movie Web 서비스를 만들면서, 각종 기능을 첨부해볼 예정
- 클론코딩 방법
    - 항상 생각하며 코딩할 것
        - 코드를 작성하기 전 코드의 의도를 생각한다
        - 이 클론 대상을 만들 때 어떤 것을 고민하였고, 어떻게 구현할 것인가를 생각하기
    - 문서화
    - 스터디에서 끝이 아니라 자신만의 앱으로 만들기(나의 색 입히기)

### 공부한 내용

- React의 탄생
- Events in React
- JSX
- State
- setState
- State Functions
- Inputs and State
- Props
- Prop Types
- CRA(Create React App)
- useEffect
- Movie App 구현 및 Publishing

### 필요한 사전지식

- HTML, CSS 기초지식
- JavaScript 기초지식

### 스터디 완료 이후

- 프론트에서 한단계 나아가기
    - 나 혼자 사이트를 만들어보기
        - 이제 진짜 프론트 개발자가 되기 위한 첫걸음을 뗀 것
        - 스크롤 내려도 상단고정되는 navbar컴포넌트 못만들겠어요…
            - 리액트가 문제가 아니라 HTML,CSS를 못하는 것
        - 상품 가나다순 정렬기능을 못만들겠어요…
            - 리액트가 문제가 아니라 자바스크립트를 못하는 것
    - 위처럼 기초 문제를 계속 프로젝트를 진행하며 점검해볼 것
        - JS실력 없는 React는 사상누각
    - firebase 이용해 나만의 웹서비스 프로토타입 만들기
    - Node.js + Express 이용(이전 Blog_Project 리팩토링) 서버기능 추가하기
- 타 사이트 카피해보기
    - 저런 사이트를 리액트로 만드려면 어떻게 해야할지 생각하고 구체화한 뒤 구현하기
- 위의 탐구 후 직접 Apple 홈페이지 같은 애니매이션 만들어보기
- 협업 경험 쌓기
    - 백엔드 개발자 친구 및 동료 찾기
    - 서로 상호작용(공생) 하며 프로젝트 완성하기

### 시연영상

[![Video Label](http://img.youtube.com/vi/9wNHVDqKUDs/0.jpg)](https://youtu.be/9wNHVDqKUDs)

[![Video Label](http://img.youtube.com/vi/VXzTa9hU6tY/0.jpg)](https://youtu.be/VXzTa9hU6tY)

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
