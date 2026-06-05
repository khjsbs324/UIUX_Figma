
코딩할 때 여러 개의 박스를 한 줄로 예쁘게 정렬하고 싶다면? 부모 요소에 디스플레이** **플렉스**(display: flex)**를 적용하고, 저스티파이 컨텐트**(justify-content)**로 정렬 방식을 정해주면 돼.
## 1. 여러 개의 박스 만들기: 젠코딩 


- 코딩할 때 똑같은 코드를 여러 번 쓰는 건 너무 귀찮잖아? 
  - 이럴 때 **젠코딩**이라는 마법을 쓰면 돼. 
  - 예를 들어, SCT01_BOX$라고 쓰고 *5를 붙이면, SCT01_BOX01부터 SCT01_BOX05까지 다섯 개의 박스 코드가 한 번에 만들어져. 
  - 여기서 $는 숫자가 자동으로 늘어나게 해주는 표시이고, *5는 5번 반복하라는 뜻이야. 
- 이렇게 만들어진 박스들은 나중에 CSS로 꾸며줄 거야. 

## 2. CSS 코드 작성 규칙: 약속 지키기 
<gen-svg-visual description="A hierarchical diagram showing the standard order of CSS styling. At the top is HTML, followed by HEAD and BODY. Under BODY, the diagram shows a vertical flow: BODY -> HEADER -> MAIN -> SECTION -> BOX. Arrows indicate the 'parent-child' relationship, emphasizing that CSS rules should be written in the same order as the HTML structure to maintain consistency and readability. The diagram visually reinforces the idea of 'not cutting in line' in CSS." />

- CSS 코드를 쓸 때는 약속이 있어. 
  - HTML 구조처럼 위에서 아래로 순서대로 쓰는 거야. 
  - 예를 들어, 가장 큰 **HTML** 안에 **BODY**가 있고, **BODY** 안에 **HEADER**, **MAIN**, **SECTION**이 있다면, CSS 코드도 이 순서대로 써야 해. 
  - 이건 마치 새치기하지 않는 것처럼, 개발자들 사이의 중요한 약속이야. 

## 3. 여러 박스 한 번에 꾸미기: 공통 이름 사용 


- 여러 박스에 똑같은 스타일을 주고 싶을 때, 박스마다 일일이 코드를 쓰는 건 비효율적이야. 
  - 이럴 땐 모든 박스에 **공통된 이름**을 하나 더 붙여주는 거야. 
  - 예를 들어, SCT01_BOX01부터 SCT01_BOX05까지의 박스들에 SCT_BOX라는 공통 이름을 추가하는 거지. 
  - 그러면 CSS에서 .SCT_BOX라고 한 번만 써도 모든 박스에 똑같은 스타일(예: 너비 100px, 높이 100px)이 적용돼. 
  - 이렇게 하면 코드를 훨씬 간결하게 만들 수 있어. 

## 4. 박스 정렬하기: 플렉스**(Flex)** 사용 


- 기본적으로 박스들은 세로로 줄줄이 나타나. 
  - 이걸 가로로 한 줄에 예쁘게 정렬하고 싶을 때 **플렉스(Flex)**라는 기능을 사용해. 
  - 박스들을 감싸고 있는 **부모 요소** (예: SCT01)에 display: flex라는 코드를 넣어주면 돼. 
  - 이렇게 하면 부모 요소가 "나 이제 내 자식들을 유연하게 배치할 거야!"라고 선언하는 셈이야. 

## 5. 박스 위치 조절하기: 저스티파이 컨텐트**(justify-content)** 


- **플렉스**를 적용한 다음에는 박스들을 어디에 놓을지 정할 수 있어. 
  - justify-content라는 코드를 사용하면 돼. 
  - 이 코드는 부모 요소에 적용해야 해. 
  - 몇 가지 옵션이 있어:
  - center: 박스들을 가운데로 모아줘. 
  - flex-start: 박스들을 왼쪽(시작 지점)으로 보내줘. 
  - flex-end: 박스들을 오른쪽(끝 지점)으로 보내줘. 
- 이 규칙들은 HTML과 CSS를 만든 사람들이 정한 약속이니까, 그냥 외워서 사용하면 돼. 

## 6. 박스 사이 간격 조절하기: 갭**(gap)** 


- 박스들 사이에 여백을 주고 싶을 때도 부모 요소에 코드를 넣어줘. 
  - gap이라는 코드를 사용하고, 원하는 간격(예: 20px)을 적어주면 돼. 
  - 이렇게 하면 박스들 사이에 일정한 간격이 생겨서 더 깔끔하게 보여. 
