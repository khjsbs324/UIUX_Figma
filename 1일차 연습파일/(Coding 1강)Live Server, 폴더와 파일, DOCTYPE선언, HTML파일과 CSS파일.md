
코딩을 배울 때 가장 중요한 건 뭘까? **폴더와 파일의 개념을 정확히 구분하는 것**이야. 이걸 알아야 코딩 수업을 제대로 따라갈 수 있고, 웹사이트를 만들 때도 기본을 탄탄히 다질 수 있어.
## 1. 폴더와 파일의 차이점 
<gen-svg-visual description="A visual representation distinguishing between a folder and a file. A folder is depicted as a container or a basket, capable of holding multiple files or other folders. A file is shown as a single document or item that cannot contain other files or folders within itself. Arrows indicate that files go into folders, but not vice versa." />

- **폴더**는 바구니처럼 다른 파일이나 폴더를 담을 수 있는 공간이야. 
  - 예를 들어, 'UIUX 피그마'라는 이름의 바구니(폴더) 안에 'HTML'이라는 파일이 들어있는 식이지. 
- **파일**은 그 자체로 하나의 내용물이야. 
  - 파일 안에는 다른 파일이 들어갈 수 없어. 

## 2. 파일의 신분증, 확장자 
<gen-svg-visual description="An illustration showing various file icons, each with a different extension (e.g., .psd for Photoshop, .ai for Illustrator, .html for HTML). The extensions are highlighted as 'ID cards' that help the computer identify what kind of file it is and which program should open it." />

- 파일 이름 뒤에 붙는 '.html', '.css' 같은 것을 **확장자**라고 불러. 
  - 확장자는 파일의 신분증 같은 역할을 해. 
  - 컴퓨터가 이 신분증을 보고 어떤 종류의 파일인지 알아차리는 거야. 
  - 예를 들어, 포토샵 파일은 '.psd', 일러스트 파일은 '.ai', HTML 파일은 '.html' 확장자를 가지고 있어. 

## 3. 웹 브라우저의 문, DOCTYPE 선언 
<gen-svg-visual description="A metaphor of a school building with a main entrance. The 'DOCTYPE html' declaration is represented as the 'door' to the school. Without this door, students (HTML files) cannot enter the school (web browser). The visual emphasizes that DOCTYPE is essential for the web browser to correctly interpret and display the HTML file." />

- **DOCTYPE** (독타입)은 웹 브라우저가 HTML 파일을 올바르게 읽을 수 있도록 알려주는 일종의 '문'이야. 
  - 학원에 들어가려면 문이 있어야 하는 것처럼, 웹 브라우저가 HTML 파일을 열려면 DOCTYPE 선언이 꼭 필요해. 
  - 이 문이 없으면 웹 브라우저는 HTML 파일을 어떻게 해석해야 할지 몰라서 제대로 보여줄 수 없어. 

## 4. HTML 버전과 구조 
<gen-svg-visual description="A timeline showing different versions of HTML (e.g., HTML 1, 2, 3, 4, 5). Each version is depicted with a slightly different structural blueprint or architecture. An arrow points from the DOCTYPE declaration to the specific HTML version, indicating that DOCTYPE tells the browser which blueprint to use. A warning sign shows what happens if the DOCTYPE doesn't match the code's structure." />

- HTML도 시간이 지나면서 계속 발전해서 여러 **버전**이 있어. 
  - 우리가 주로 배우는 건 HTML5 버전이야. 
- 각 버전마다 HTML 파일의 **구조**가 조금씩 달라. 
  - DOCTYPE 선언은 웹 브라우저에게 "나는 HTML5 기준으로 만들어졌으니, HTML5 규칙에 맞춰서 읽어줘!"라고 알려주는 역할을 해. 
  - 만약 DOCTYPE이 HTML4라고 되어 있는데, 코드는 HTML5 기준으로 작성하면 웹 브라우저가 혼란스러워할 수 있어. 
  - 그래서 기존에 만들어진 HTML 파일의 DOCTYPE이나 구조를 함부로 바꾸면 안 돼. 

## 5. HTML 파일의 두뇌와 몸통: <head>와 <body> 
<gen-svg-visual description="A human body divided into two main sections: the head and the body. The head section is labeled '<head>' and contains elements like 'thoughts' or 'information storage' (e.g., meta-information, links to <keyword data-source-id=" />

- HTML 파일은 크게 두 부분으로 나눌 수 있어. 
  - <head> (헤드): 사람의 머리처럼 생각하고 정보를 저장하는 공간이야. 
  - 웹 페이지의 제목, 다른 파일(CSS)과의 연결 등 눈에 보이지 않는 중요한 정보들이 여기에 들어가. 
  - <body> (바디): 사람의 몸통처럼 실제로 화면에 보이는 내용들을 담는 공간이야. 
  - 글자, 이미지, 버튼 등 사용자가 직접 보고 상호작용하는 모든 요소들이 여기에 만들어져. 

## 6. HTML과 CSS의 역할 분담 
<gen-svg-visual description="A person's body (HTML) is shown, initially 'naked' or unstyled. Then, various clothes (CSS) are added to the body, making it look stylish and colorful. This illustrates that HTML creates the basic structure (the body), and CSS adds the styling and appearance (the clothes)." />

- **HTML**은 웹 페이지의 뼈대나 몸통을 만드는 역할을 해. 
  - 예를 들어, <div> (디브) 같은 태그(뼈대)를 만들면, 아무 의미 없는 빈 상자가 하나 생기는 거야. 
- **CSS**는 이 뼈대에 옷을 입히고 꾸며주는 역할을 해. 
  - HTML로 만든 빈 상자에 색깔을 넣거나 크기를 조절하는 등의 디자인을 담당하는 거지. 
  - CSS 파일은 보통 'style.css'라는 이름으로 만들어. 

## 7. CSS 파일 연결하기 
<gen-svg-visual description="A diagram showing the HTML file and the CSS file as two separate entities. A 'link' tag within the <head> section of the HTML file is depicted as a bridge connecting the HTML file to the CSS file. This visually explains how HTML 'knows' to use the styles defined in the CSS file." />

- HTML 파일이 CSS 파일의 디자인을 사용하려면, 두 파일을 서로 **연결**해줘야 해. 
- 이 연결은 HTML 파일의 <head> 안에 <link> 태그를 사용해서 해. 
  - <link rel="stylesheet" href="style.css"> 이렇게 작성하면, HTML 파일이 'style.css' 파일에 있는 디자인 규칙을 가져와서 적용하게 돼. 

## 8. 웹 페이지 미리보기: Live Server 
<gen-svg-visual description="A split screen showing a code editor on one side and a web browser on the other. An arrow labeled 'Live Server' connects the two, indicating that changes made in the code editor are instantly reflected in the web browser without manual refreshing. This highlights the convenience of Live Server for real-time development." />

- 코드를 작성할 때마다 웹 페이지가 어떻게 보이는지 바로바로 확인하려면 **Live Server** (라이브 서버)라는 도구가 필요해. 
  - Live Server는 코드를 저장할 때마다 웹 브라우저에 자동으로 변경된 내용을 보여줘. 
  - 이 도구가 없으면 코드를 조금만 바꿔도 매번 새로고침을 눌러야 해서 불편해. 
- Live Server는 비주얼 스튜디오 코드(Visual Studio Code)의 **확장 프로그램**으로 설치할 수 있어. 
  - 설치 후 HTML 파일에서 마우스 오른쪽 버튼을 눌러 'Open with Live Server'를 선택하면 돼. 

## 9. 개발자 도구 활용하기 


- 웹 페이지가 제대로 만들어졌는지 확인하고 싶을 때 **개발자 도구**를 사용할 수 있어. 
  - 키보드의 **F12** 버튼을 누르면 개발자 도구가 열려. 
  - 이 도구에서는 웹 페이지의 HTML 구조와 CSS 스타일이 어떻게 적용되었는지 자세히 볼 수 있어. 
  - 예를 들어, <div> 태그에 빨간색 배경이 잘 적용되었는지 확인할 수 있지. 

## 10. DIV 태그로 상자 만들기 


- <div> (디브) 태그는 웹 페이지에서 가장 기본적인 '의미 없는 상자'를 만들 때 사용해. 
  - 이 상자는 그 자체로는 아무런 디자인이 없어. 
- <div> 태그에 디자인을 입히려면 CSS 파일에서 꾸며줘야 해. 
  - CSS 파일에 div { background-color: red; width: 500px; height: 500px; } 이렇게 작성하면, <div> 상자에 빨간색 배경과 가로세로 500픽셀 크기가 적용돼. 
  - 너비 (width)와 높이 (height)를 지정해야 화면에 상자가 보이게 돼. 크기가 없으면 눈에 보이지 않거든. 

## 11. 피그마와 코딩의 관계 
<gen-svg-visual description="A two-panel diagram. The left panel shows a design created in Figma, with design properties (e.g., color, size, font) clearly visible. The right panel shows corresponding HTML and CSS code snippets. An arrow points from Figma's design properties to the code, illustrating how Figma can generate or inspire the code, making the design-to-code process more efficient. This emphasizes that Figma is a design tool that helps in coding." />

- 피그마 (Figma)는 웹 페이지 디자인을 미리 만들어보는 도구야. 
  - 피그마에서 디자인한 내용을 바탕으로 HTML과 CSS 코드를 작성하면, 디자인과 코딩 작업을 효율적으로 할 수 있어. 
  - 디자인 도구인 피그마와 코딩은 서로 뗄 수 없는 관계야. 

