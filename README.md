# 5주차 과제 

## 웹페이지 소개
-독일어 공부를 시작하는 사람들을 위한 홈페이지

-독일어 회화를 연습하고 싶은 사람들을 위한 사이트

-독일 문화에 관심을 갖고 있는 사람들을 위한 공간

<img src="./images/05.png" width="450px" height="300px" title="홈페이지" alt="홈페이지 home 사진"></img><br/>

--------------------------------
## 주요 코드 설명

1. Transition

    크기, 색 등을 변화시키는 코드

    transition-delay: 몇초 후 재생 <br/>
    transition-duration: 몇초동안 재생 <br/>
    transition-property: 어떤 속성 변형 <br/>
    transition-timing-function: 수치 변형 함수 지정 <br/>
         *cubic-bezier(x1,x2,y1,y2)*

2. Transform

    2D, 3D 표현 및 상태를 변화시키는 코드

    trasition: translate (X,Y) 이동 <br/>
               scale (X,Y) 축소 <br/>
               skew (X,Y) 기울임 <br/>
               rotate (X,Y) 회전 <br/>

    *3D는 transition 3D*



3. Animation

    움직임을 진행시키는 코드

    animation-delay: 지연시간 <br/>
    animation-direction: 방향 (일방향/왕복) <br/>
    animation-duration: 재생시간 <br/>
    animation-iteration-count: 반복횟수 <br/>
    animation-name: 이름 *@keyframes* <br/>
    animation-play-state: 재생상태 (움직임/정지) <br/>
    animation-function: 타이밍함수 <br/>


<br/>

### 핵심코드

1. CSS 

    외부 CSS 연결

    link rel="stylesheet" href="css/파일명.css"

2. Banner
    
    -animation

    @keyframes <애니메이션이름> 으로 이름설정 (slide, opacity)

    animation-duration: 재생시간 설정
    
    animation-iteration-count: 반복횟수 설정


3. Side-menu

    -css를 이용하여 사이드 메뉴를 만들고 버튼을 누르면 사이드 메뉴가 보이게끔 함.

    -java script 내용 포함
    (버튼을 누른다는 조건을 설정하여, 눌렀을 때 사이드 메뉴가 나타나게 하는 것)


<br/>

### 코드분석

    1. banner.css 를 생성하여 'Willkommen!, 환영합니다'에 애니메이션 효과를 부여함. 
         Willkommen!: slide (천천히 밀면서 나타남)
         환영합니다: opacity (흐릿하게 나타나서 진해짐)

    2. side-menu.css 를 생성하여 사이드 메뉴를 만듦.
        java script 내용이 포함되어 있음.


-----------------------------------

## 비고 및 고찰
1. 자바스크립트가 세부적인 내용까지 다룰 수 있을 것으로 기대되어 빨리 학습하고 싶다.
2. 코드들을 따로 배울 때는 이해가 갔지만, 실제로 여러코드를 같이 적용하려고 하니 코드가 겹쳐서 어려움을 겪었다.