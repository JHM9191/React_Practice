# React 공부



생활코딩에서 공부하고 있습니다.





### React 가 무엇인가요?

- 래엑트는 페이스북 닷컴의 UI를 더 잘만들기 위해서 나오게됨
- 페이스북에서 만든 JavaScript UI Library 이다



### React의 특징

- 컴포넌트를 사용한다.





1. 가독성이 높다
2. 재사용성이 높다
3. 유지보수가 쉽다.



### React 프로젝트 만들기

##### #방법 1

```bash
npx create-react-app my-app
```

- `npx` 
  - npm을 사용해서 `create-react-app`을 1회 다운받고 실행하고 지워버린다.
  - 사용하는 이유는 항상 최신 버전의 `create-react-app`을 다운 받아주기 때문이다.

##### #방법 2

```bash
npm create-react-app my-app
```



​          



### React 프로젝트 배포하기

```bash
npm run start
```



- React-create-app 으로 새로운 프로젝트를 생성하게 되면  react 의 이것 저것 필요한 모듈들 여러개 설치가 되면서 프로젝트가 무거워지고 
- 이 앱을 바로 서버에 올리게되면 사용자들이 이 무거운 프로젝트를 실행하게 되는데.
- 실제로 사용되고 있는 모듈 등으로만 파일을 정리하고 이 파일을 배포하는 명령어는 다음과 같다.

```bash
npm run build
```

```bash
npx serve -s build
```

- Serve 라는 웹서버를 다운 받아서 실행시킬 때 build 라는 우리가 생성한 디렉토리를 Document root로 실행하는 것이다.

​          



### Component 생성하기

