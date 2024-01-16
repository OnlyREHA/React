

![image](https://github.com/OnlyREHA/React/assets/145514740/42dbd808-8157-407a-b6df-b1ed1986cf91)


### Navigate 사용방법  --> 어떤 페이지로 강제 이동(리다이렉트)
react-router-dom 의 compoent

![image](https://github.com/OnlyREHA/React/assets/145514740/61048901-ba1a-4490-82c4-9c99d55754ee)

### useParams
react-router-dom 의 hook

```
http://localhost:3000/product/0
```

0 =>

- url 주소에서 파라미터는 제일 뒤에 있는 0이라는 숫자이다
- id값이 들어와 있다
- 파라미터값을 읽어와야할때 useParams hook이다

- ![image](https://github.com/OnlyREHA/React/assets/145514740/f4134c8a-fd2f-4cb9-b595-ee38dc9f9b7d)

### 문법  --> ?
```
 <img src={product?.img} alt="" />
```
product?.img => product가 있으면 product.img를 출력하도록 함


### 💠 쿼리스트링 
```
쿼리스트링(query string)은 웹 주소(URL)에 추가적인 매개변수를 전달하는 방법 중 하나입니다.
쿼리스트링은 URL의 끝에 "?" 문자로 시작하며, 이후에 "이름=값" 형태의 매개변수들이 "&" 문자로 구분되어 나열됩니다.
```

 navigate(`/?q = ${keyword}`  --> 쿼리스트링(query string) 입력하기




