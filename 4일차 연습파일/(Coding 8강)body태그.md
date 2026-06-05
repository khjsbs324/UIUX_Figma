​
바디(body) 태그는 왜 필요할까? 바디 태그는 웹사이트가 **다양한 기기에 맞춰 화면 크기를 조절(**반응형**)**하고, **사이트의 전체 높이를 감지해 스크롤을 자동으로 만들어주는** 아주 중요한 역할을 해.
## 1. 웹페이지의 기본 구조: <body> 태그 
<gen-svg-visual description="A simple diagram showing the basic structure of an HTML page. It illustrates the <html> tag as the outermost container, with <head> and <body> tags nested inside. The <head> contains metadata (like title, links to <keyword data-source-id=" />

- 웹페이지는 크게 두 부분으로 나눌 수 있어.
  - <head> (머리): 웹페이지의 제목이나 스타일(CSS), 스크립트(JavaScript) 같은 정보를 담는 곳이야. 우리가 눈으로 직접 볼 수 있는 내용은 없어.
  - <body> (몸통): 우리가 웹사이트에 접속했을 때 눈으로 보고 상호작용하는 모든 내용이 들어가는 곳이야. 글, 이미지, 버튼 등 모든 시각적인 요소들이 여기에 담겨 .
- 이 <body> 태그 안에 <header>(머리글), <main>(본문), <footer>(꼬리글) 같은 태그들을 넣어서 웹페이지의 각 부분을 만들 수 있어 .
  - 예를 들어, 헤더는 86픽셀, 메인 부분은 화면 높이의 4배(400VH), 푸터는 68픽셀로 높이를 정할 수 있어 .

## 2. <body> 태그의 놀라운 능력: 반응형 웹과 스크롤 자동 생성 


- <body> 태그는 웹페이지를 똑똑하게 만들어주는 중요한 역할을 해.
  - **반응형 웹 (Responsive Web)**: 우리가 웹사이트를 컴퓨터, 태블릿, 스마트폰 등 다양한 기기에서 볼 때, 화면 크기에 맞춰 웹페이지가 자동으로 조절되는 걸 **반응형**이라고 해 .
  - <body> 태그는 접속한 기기의 화면 너비를 읽어서 웹페이지가 그 크기에 딱 맞게 보이도록 해줘 . 마치 옷이 사람 몸에 맞춰 늘어나고 줄어드는 것처럼 말이야.
  - 만약 <body> 태그가 없다면 이런 똑똑한 기능은 불가능해 .
  - **스크롤 자동 생성**: 웹페이지 내용이 화면 높이보다 길어지면, <body> 태그가 이걸 감지해서 자동으로 스크롤바를 만들어줘 .
  - 마치 두루마리 휴지가 길어지면 자동으로 돌돌 말리는 것처럼, 내용이 많아지면 스크롤이 생겨서 모든 내용을 볼 수 있게 해주는 거지 .

## 3. <body> 태그의 숨겨진 기본 여백 
<gen-svg-visual description="A diagram illustrating the default margin around the <body> tag. It shows a browser window with a webpage content area. Around the content area, there's a thin, uniform gray border representing the default margin applied by the browser to the <body> tag. An arrow points to this border, labeling it 'Default Margin (Margin/<keyword data-source-id=" />

- <body> 태그에는 우리가 따로 설정하지 않아도 기본적으로 **여백**이 있어 .
  - 마치 책의 페이지 가장자리에 글이 잘리지 않도록 여백이 있는 것과 같아 .
  - 이 여백은 웹페이지를 만들 때 개발자들이 내용을 보기 편하게 하려고 넣어둔 거야 .
- 하지만 우리는 직접 디자인을 해야 하니까, 이 기본 여백이 방해가 될 때가 많아 .
  - 그래서 보통은 이 여백을 없애고 우리가 원하는 대로 디자인을 시작해 .
  - 여백을 없애는 방법은 <body> 태그에 margin: 0;과 padding: 0;을 설정해 주는 거야 .
  - margin (마진)은 요소의 **바깥쪽 여백**을, padding (패딩)은 요소의 **안쪽 여백**을 조절하는 코드라고 보면 돼 .

## 4. CSS 노멀라이즈: 웹페이지 스타일 통일하기 
<gen-svg-visual description="A flowchart illustrating the process of CSS normalization. It starts with 'Browser Default Styles (different across browsers)'. An arrow leads to 'Apply Normalize.css or Reset CSS'. This step then points to 'Consistent Base Styles for All Elements'. Finally, an arrow leads to 'Developer's Custom Styles', indicating that normalization provides a clean slate for custom design. The diagram highlights that normalization ensures a consistent starting point for styling across different browsers." />

- 웹 브라우저마다 웹페이지를 보여주는 방식이 조금씩 다를 수 있어. 그래서 어떤 브라우저에서는 예쁘게 보이던 페이지가 다른 브라우저에서는 이상하게 보일 수도 있거든.
- 이런 문제를 해결하기 위해 CSS** 노멀라이즈 (CSS Normalize)**라는 걸 사용해 .
  - 이건 모든 브라우저에서 웹페이지가 똑같은 기본 스타일로 시작하도록 만들어주는 작업이야 .
  - 마치 모든 학생에게 똑같은 새 스케치북을 나눠주고 그림을 그리게 하는 것과 같아.
- 노멀라이즈를 할 때는 보통 normalize.css 같은 별도의 CSS 파일을 만들어서 사용해 .
  - 이 파일에서 <body> 태그의 기본 여백(margin, padding)을 0으로 설정하는 등의 작업을 해줘 .
  - 이렇게 하면 우리가 원하는 디자인을 더 쉽게 만들 수 있어 .
