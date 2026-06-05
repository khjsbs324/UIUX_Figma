​
다양한 크기의 박스들을 만들 때 어떻게 해야 할까? 클래스**(class)**를 각각 다르게 지정해서 박스마다 다른 크기를 줄 수 있어. 이렇게 하면 여러 박스를 만들 때도 각각의 크기를 쉽게 조절할 수 있는 거야.
## 1. 여러 박스를 만들 때, 각각 다른 크기를 주는 방법 
<gen-svg-visual description="A diagram showing five boxes of different sizes. Each box is labeled with 'nav-box-01', 'nav-box-02', etc., indicating they have different classes to allow for individual sizing. Arrows point from each box to a corresponding class name, emphasizing the one-to-one relationship between a box and its unique class for custom dimensions." />

- 여러 개의 박스를 만들 때, 각각 다른 크기를 주고 싶을 때가 있어. 
- 예를 들어, 메뉴바에 있는 버튼들이 크기가 다를 수 있잖아. 
- 이럴 때는 각 박스에 클래스**(class)**라는 이름을 다르게 붙여주면 돼. 
  - 클래스는 박스마다 붙이는 고유한 이름표 같은 거야. 
  - 이름표가 다르면, 각 박스에 "너는 이만큼 커져라", "너는 저만큼 작아져라" 하고 따로따로 명령을 내릴 수 있거든. 

## 2. HTML에서 박스 만들기: div 태그와 클래스 이름 붙이기 


- 박스를 만들 때는 보통 div라는 태그(꼬리표)를 사용해. 
  - div는 "의미 없는 박스"라는 뜻인데, 그냥 공간을 나누는 데 많이 쓰여. 
- 여러 개의 div 박스를 한 번에 만들면서 클래스 이름도 자동으로 붙일 수 있는 편리한 방법이 있어. 
  - div.nav-box-0$*5 라고 입력하고 탭(Tab) 키를 누르면 돼. 
  - div: 박스를 만들 거야.
  - .nav-box-0$: 클래스 이름은 nav-box-0로 시작하고, 뒤에 숫자가 붙을 거야. ($는 숫자가 자동으로 증가한다는 뜻이야.)
  - *5: 이런 박스를 5개 만들 거야.
  - 이렇게 하면 nav-box-01, nav-box-02, ..., nav-box-05 같은 클래스 이름을 가진 div 박스 5개가 한 번에 만들어져. 
- 클래스 이름은 다른 것과 헷갈리지 않게 nav-box-01처럼 대시(-)를 쓰는 게 좋아. 
  - 언더바(_)는 자바스크립트(다른 프로그래밍 언어)에서 주로 쓰기 때문에 헷갈릴 수 있거든. 

## 3. CSS로 박스 크기와 모양 꾸미기 


- HTML로 박스를 만들었으면, 이제 CSS(꾸미기 언어)로 박스의 크기나 색깔 같은 걸 정해줄 차례야. 
- CSS에서 특정 클래스를 가진 박스를 꾸미려면, 클래스 이름 앞에 점(.)을 붙여야 해. 
  - 예를 들어, nav-box-01 클래스를 가진 박스를 꾸미려면 .nav-box-01이라고 써야 해. 
- 박스의 크기를 정할 때는 너비**(width)**와 높이**(height)**를 픽셀(px) 단위로 지정해줘. 
  - 예를 들어, width: 92px;는 너비를 92픽셀로, height: 12px;는 높이를 12픽셀로 만들라는 뜻이야. 
- 박스에 색깔을 넣고 싶으면 배경색**(background-color)**을 지정할 수 있어. 
- **모서리 둥글게 만들기 (**border-radius**)** 
  - border-radius라는 속성을 사용하면 박스의 딱딱한 모서리를 둥글게 만들 수 있어. 
  - 마치 종이 모서리를 가위로 둥글게 자르는 것과 같다고 생각하면 돼. 
  - 디자인 도구(피그마)에서 본 모양을 코딩으로 똑같이 옮겨보는 연습을 하면 코드를 더 쉽게 이해하고 외울 수 있을 거야. 
