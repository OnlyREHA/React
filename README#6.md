# useEffect

### useEffect(( ) => { },[ ])

![image](https://github.com/OnlyREHA/React/assets/145514740/be271ff4-6691-4929-860d-a09f428b6e02)

useEffect(( ) => { },[ ]) => 배열이 비어있을 경우에는 component가 실행될때 처음 한번만 실행된다.

---

![image](https://github.com/OnlyREHA/React/assets/145514740/b65955f7-18ab-4b29-b9ef-bf8749b11a3d)

useEffect(( ) => { },[products])  => component의 값이 바뀔때마다 useEffect가 실행됨 (component가 실행될때 처음 한번 실행됨)

useEffect(( ) => { },[products, count])  => componentrk 실행될때 처음 한번 실행된후 products와 count중에 하나라도 값이 바뀌면 useEffect가 실행됨 (2개가 다 바뀌어도 한번 실행됨)

---

![image](https://github.com/OnlyREHA/React/assets/145514740/0070c1ce-bb73-425d-9f40-5f4df7a637f3)

useEffect()가 종료되는 시점에 변경된다.






