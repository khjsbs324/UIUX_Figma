
코딩할 때 배경색을 왜 써야 할까? 눈으로 보기에 똑같아 보여도, 배경색을 칠해보면 요소들의 **정확한 위치와 크기**를 파악해서 레이아웃(화면 배치)을 쉽게 잡을 수 있기 때문이야.### 1. 웹 페이지 레이아웃(화면 배치)의 중요성 <gen-svg-visual description="A simple web page layout with a navigation bar, logo, and user menu. Each element is represented by a box, and they are arranged horizontally within a header box. Arrows indicate the flow of arrangement." />
- 웹 페이지를 만들 때, 화면에 요소들을 어떻게 배치할지 정하는 걸 **레이아웃**이라고 해 
  - 예를 들어, 내비게이션 바(메뉴), 로고, 사용자 메뉴 같은 것들이 나란히 놓여야 할 때가 많아 
- 이런 요소들을 정확하게 원하는 위치에 놓는 게 중요해 
## 2. 요소들을 한 줄로 나열하는 방법: 플렉스(Flex) 


- 여러 요소를 가로로 나란히 놓으려면, 그 요소들을 감싸는 큰 상자(태그)에 **플렉스(Flex)**라는 기능을 적용해야 해 
  - 마치 여러 친구를 한 줄로 세우기 위해 "줄 서!"라고 명령하는 것과 같아 
  - 이렇게 하면 요소들이 자동으로 옆으로 나란히 정렬돼 
### 3. 요소의 위치와 크기를 정확히 파악하는 비법: 배경색 칠하기 


- 눈으로 보기에는 요소들이 잘 놓인 것 같아도, 실제로는 위치나 크기가 미묘하게 다를 수 있어 
  - 이럴 때 각 요소에 **배경색(background-color)**을 칠해보면 정확한 위치와 크기를 한눈에 알 수 있어 
  - 마치 투명한 상자들을 색깔 있는 상자로 바꿔서 어디부터 어디까지인지 명확하게 보는 것과 같아 
- 배경색을 칠하면 어떤 요소가 다른 요소와 겹치거나, 너무 크거나 작은지 쉽게 파악해서 레이아웃 문제를 해결할 수 있어 

## 4. CSS 선택자(Selector)로 요소에 스타일 적용하기 
<gen-svg-visual description="A diagram illustrating different types of CSS selectors. It shows a 'Header' box containing 'H1 (Logo)', 'Nav (Navigation)', and 'User Box (Class: user-box)'. Arrows point from CSS code snippets to the corresponding elements they would select. Examples include 'nav { ... }' pointing to 'Nav', 'h1 { ... }' pointing to 'H1', and '.user-box { ... }' pointing to 'User Box'." />

- 웹 페이지의 특정 요소에 배경색 같은 스타일을 적용하려면, 어떤 요소에 적용할지 정확히 알려줘야 해 
  - 이걸 **선택자(Selector)**라고 부르는데, 크게 두 가지 방법이 있어 
  - 태그 선택자: HTML 태그 이름(예: nav, h1)을 직접 써서 선택하는 방법이야 
  - 예를 들어, <nav> 태그에 스타일을 적용하고 싶으면 nav { ... }라고 쓰는 거지 
  - 클래스 선택자: HTML 요소에 class="이름"처럼 이름을 붙여주고, CSS에서는 .(점)을 붙여서 선택하는 방법이야 
  - 예를 들어, class="user-box"인 요소에 스타일을 적용하고 싶으면 .user-box { ... }라고 쓰는 거야 
- 이렇게 선택자를 사용해서 원하는 요소에만 배경색을 칠하거나 다른 스타일을 적용할 수 있어 
