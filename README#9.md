# JsonServer사용

📌 작은 서버를 만드는 것 

-> api 소통할때 제일 많이 쓰이는 파일타입

![image](https://github.com/OnlyREHA/React/assets/145514740/d3b20f26-2716-4bd2-8bbd-24c1068bbe65)

### [1] JsonServer 연결
```
npm install -g json-server
```

### [2] 확장명 .Json인 파일을 만든다  --> 반드시 Root자리에 만들어야한다

![image](https://github.com/OnlyREHA/React/assets/145514740/c0ab2f40-f7fc-45ed-b6b5-3decfa99fb52)

### [3] JsonServer 실행  
```
json-server --watch db.json --port 3004
```
--> 기본적으로 3000번에서 시작하는데 react와 겹치지 않게 다른 포트번호를 설정해야한다.

❌ 실행이 안될경우
```
npx json-server --watch db.json --port 3004
```

- Jsonserver 연결확인
```
http://localhost:3004/products
```

![image](https://github.com/OnlyREHA/React/assets/145514740/1b7c306c-d2cb-402d-84c3-023b71319152)

  
