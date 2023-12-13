## app추가하기

```
npm create-react-app 폴더명
```

## 기본다시해보기
![image](https://github.com/OnlyREHA/React/assets/145514740/b86d67ae-7464-42ba-bd8f-02bf727d7d59)

![image](https://github.com/OnlyREHA/React/assets/145514740/d4c91fbf-4a3d-47b5-8233-4546576b3ff2)

- react에서는 데이터를 변할수 있는 값이고, 값이 변할때마다 UI를 변경해 달라고(화면을 다시 그려달라) 알려야 한다.
- 그럴때 사용하는것이 useState() 이다.

  const [num, setNum] = useState(0)

- 이 데이터를 변할수 있는 값 => num
- num을 변하게 하는 함수 => setNum (함수를 이용하여 num을 변경한다)
- useState(0)의 0은 num의 초기값

  ## 부분적으로 값 받기

  ![image](https://github.com/OnlyREHA/React/assets/145514740/88f71892-47fa-45e7-99e2-90c7c2bb512c)

  ![image](https://github.com/OnlyREHA/React/assets/145514740/6c51f1f8-c69c-4583-985c-ea2ccd5ed9cc)


  ## 구조분해

```
  import React from 'react'

  const Profile = ({img,name,title,isNew}) => {
  // const img = props.img;
  // const name = props.name;
  // const title = props.title;

  //구조분해 
  //const {img,name,title,isNew} = props;
  return (
    <>
      <div className='profile'>
        <img src={img} alt="Doraemon" />
        {/* {props.isNew?<span className='new'>신입</span>:""} */}
        {isNew && <span className='new'>신입</span>}
        <h2>{name}</h2>
        <p>{title}</p>
      </div>
    </>
  )
}

export default Profile
```








