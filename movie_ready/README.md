React로 영화 웹 서비스 만들기

Babel => jsx문법을 사용해서 작성한 코드를 브라우저가 이해할수 잇는 형태로 변환해준다. 
      => jsx를 react js로 변환

컴포넌트의 첫글자는 반드시 대문자여야 한다. 소문자로사용하면 html요소가 된다.
대문자를 사용하여 컴포넌트인것을 알려줘야한다.

const [data, setData] = React.useState() =>2개의 값을 가지고 있는 배열하나를 반환하는데 배열의 첫번째 값은 초기값이고(data), 두번째 배열의 값은 그 값을 바꾸는 함수이다(setData()).

props => 컴포넌트에 보내는 object를 인자로 모두 받는다.

propTypes => ReactJS에서는 코드는 유효하니까 오류를 알려주지 않지만 propTypes을 이용하면 타입이 다른걸 오류로 알려준다.