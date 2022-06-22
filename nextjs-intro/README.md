## Making Movie App

### Children

: Component 안에 Component를 넣을 때 사용하는 걸 `children` 이라고 한다.

### global.css

: global.css에 css를 추가하고 (frame 같은 것) `_app.js`에서 읽어들이면 모든 page에 적용됨.

### getServerSideProps

: 이 함수를 쓰게 되면 서버에서만 동작하는 함수가 된다. 따라서 여기서 api call을 하고 이를 props로 front에 넘겨주는 방식을 취할 수 있다.
