# WebProgramming_Study

## 용어 정리

### meta
meta 태그는 웹 서버와 브라우저 간에 상호 교환되는 정보를 정의하는데 사용

검색 엔진 최적화를 하는데 중요한 태그

기본적으로 빈 요소이므로 시작 태그만 존재

- charset
  - HTML5의 인코딩을 지정하는 방법
  - meta 태그의 charset 속성은 해당 HTML 문서의 인코딩 방식을 명시
  - 일반적으로 meta charset="utf-8"을 사용

- http-equiv
  -  content 속성에 명시된 값에 대한 HTTP 헤더를 제공
  -  HTTP 응답 헤더를 시뮬레이션할 때 사용할 수 있음
  -  http-equiv 속성이 명시되어 있다면, 반드시 content 속성도 함께 명시되어야 함

ex)

+ meta http-equiv="imagetoolbar" content="no"
  + 그림위에 마우스 오버시 이미지 관련 툴바가 생기지 않도록 정의
+ meta http-equiv="X-UA-Compatible" content="IE=edge
  + IE의 버전 차이로 인해 다르게 보이지 않게 호환성 보기 기능이 활성화되도록 지정

- name
  - 메타데이터를 위한 이름을 명시
  - 만약 name 속성이 명시되었다면, 반드시 content 속성도 함께 명시
  - HTML5에서는 <meta> 요소를 통해 웹 페이지에서 사용자가 볼 수 있는 영역인 뷰포트(viewport)를 제어할 수 있도록 name 속성에 viewport 속성값을 제공
)

ex)

+ meta name="viewport" content="width=device-width,initial-scale=1.0,minimum-scale=0,maximum-scale=10,user-scalable=yes"
  +  viewport는 화면에 보이는 영역으로 너비를 현재 기기의 width로 정하고, 초기 화면 배율을 1로 지정하고 0~10까지 사용자가 스케일을 조정할 수 있도록 함

***
***

### div
Division의 약자로 웹사이트의 레이아웃(전체적인 틀)을 만들때 주로 사용

웹페이지에서 논리적 구분을 정의하는 태그

 각각의 블록(공간)을 알맞게 배치하고 CSS를 활용하여 스타일을 적용
 
***
***

### span

***
***

### id 선택자


***
***

### class 선택자


### title
브라우저 윈도우의 제목 설정

***
***

### style


***
***
#### placeholder
타입이 text인 input 요소나, textarea 태그로 만들어진 텍스트 박스에 사용자가 값을 입력 하기 전에 해당 박스에 간단한 내용을 표시해 주는 것

- :-ms-input-placeholder
  - 마이크로소프트 인터넷 익스플로러(IE)에서 잘 작동시키기 위함
- ::-ms-input-placeholder
  - 마이크로소프트 엣지에서 잘 작동시키기 위함
- ::placeholder
  -  크롬, 파이어폭스, 오페라, 사파리에서는 잘 작동시키기 위함( 마이크로소프트의 브라우저에서는 잘 안됨)
