## Node.js 설치

-자바스크립트를 브라우저 밖에서 동작할수 있도록 하는 런타임환경

-Node.js가 제공하는 것이 npm(Node Package Manger)

-npm이란 node.js로 만들어진 필요한 모듈을 다운받고 관리해줌

-다른 개발자가 만들어둔 유용한 node.js로 만들어진 툴로 가져다 쓸 수 있음

-npm을 이용한 라이브러리를 다운받을 예정



-node.js 사이트에서 설치파일을 다운로드

-윈도우 버튼에 cmd검색 후 열기, 관리자권한으로 실행

![image](https://github.com/OnlyREHA/React/assets/145514740/c43f0bde-94bb-43f4-9c1f-5ed49a032a65)


```
node -v 
```

입력 후 버전이 나오면 설치가 완료된 것

```
npm -v
```

-node.js를 설치하면 npm이 자동으로 설치됨

-npx는 npm이 설치될때 같이 설치됨

-npx란,  외부라이브러리를 쉽게 설치하고 버전을 관리 할수 있게 한다

-->  package.json을 만들게 된다

-->  라이브러리를 개별적으로 실행하고자 할때 사용하는것


### 1. 폴더생성

- 프로젝트를 만들 폴더를 만든다 ex) reha_react

### 2. 리액트에서 필요한 패키지를 자동으로 설치해주는 명령어를 입력한다.

- D드라이브안으로 이동 D:

```
npm install -g create-react-app
```

```
npx create-react-app my-app
```

차례대로 입력


### SPA: single Page Application

- 페이지는 하나인데 여러개인것처럼 눈속임을 함. (여러개인것처럼 보이지만 사실은 하나!)

- 페이지를 매번 새로 가져올 필요가 없음, 웹사이트를 모바일처럼 사용할수 있음.

### 3. react 확장프로그램 설치

- react 프로그램

![image](https://github.com/OnlyREHA/React/assets/145514740/d4e4fd83-0420-4a5d-85c8-0f0de704d9e0)

- react 코드 정렬
  
![image](https://github.com/OnlyREHA/React/assets/145514740/b45454cb-14bb-46b2-98d3-774a33b7eb13)

### 4. save 설정하기

- vs code에 설정에서 체크하기
- Default format - prettier로 설정하기 

![image](https://github.com/OnlyREHA/React/assets/145514740/c0831854-ee21-4623-bbc7-c09e8e698738)

### 5. react 실행

- 부모폴더를 끌고왔을때 실행폴더로 시작하기
- vscode 터미널에 입력
- 
```
cd 실행폴더명
``` 

vscode 터미널 실행

```
npm start
```



















