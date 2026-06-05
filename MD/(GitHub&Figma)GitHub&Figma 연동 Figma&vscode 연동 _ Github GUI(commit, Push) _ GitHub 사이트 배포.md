
GitHub, Figma, VS Code를 연동하는 가장 효율적인 방법은? **GitHub Desktop 앱**을 활용하는 거야. 코드를 수정하고 커밋(변경 사항 저장)할 때 터미널(명령어를 입력하는 창) 대신 데스크톱 앱에서 버튼만 누르면 돼서 훨씬 편하고 오류도 줄일 수 있어.
## 1. GitHub** Desktop 앱**으로 코드 관리 시작하기 
<gen-svg-visual description="A diagram showing the process of setting up GitHub Desktop. It starts with 'Download GitHub Desktop App', then 'Log in/Sign out and Log in again', followed by 'Create a New Repository (UIX Figma 2)', and finally 'Create an initial file (index.html) and commit changes'." />

- **GitHub Desktop 앱**은 코드를 관리하는 데 쓰는 프로그램이야. 마치 게임을 설치하듯이 컴퓨터에 설치해서 쓰는 거지. 
  - 이 앱을 쓰면 복잡한 명령어를 외울 필요 없이 버튼만 눌러서 코드를 저장하고 공유할 수 있어. 
- 먼저, **GitHub Desktop 앱**을 열고 로그인 상태를 확인해야 해. 
  - 혹시 다른 계정으로 로그인되어 있거나 로그인이 안 되어 있다면, **로그아웃**하고 다시 로그인해야 해. 
- 이제 새로운 **저장소(**Repository**)**를 만들어 볼 거야. 
  - 저장소는 네가 만든 코드나 디자인 파일을 모아두는 폴더라고 생각하면 돼. 
  - 이름은 'uix-figma-2'처럼 알아보기 쉽게 지어주면 돼. 
- 저장소를 만들었으면, 첫 번째 파일을 추가해 보자. 
  - 'index.html'이라는 파일을 만들고, 간단한 내용(예: 'ex')을 넣어줘. 
  - 그리고 이 변경 사항을 커밋**(Commit)**해야 해. 커밋은 '여기까지 작업했어!' 하고 기록을 남기는 거라고 보면 돼. 
  - 커밋할 때는 어떤 내용을 바꿨는지 제목과 설명을 자세히 적어주는 게 좋아. 나중에 뭘 바꿨는지 쉽게 알 수 있거든. 

## 2. GitHub Pages로 웹사이트 배포하고 **Figma**와 VS Code 연결하기 


- 네가 만든 코드를 다른 사람들이 볼 수 있는 웹사이트로 만들 수 있어. 이걸 **GitHub Pages**라고 해. 
  - 저장소 설정(Settings)에서 '페이지(Pages)' 메뉴로 들어가서, '브랜치(Branch)'를 'main'으로 바꿔주고 저장하면 돼. 
  - 이렇게 하면 네 코드가 웹사이트 주소로 바뀌어서 인터넷에 공개되는 거야. 
- 이제 **Figma**와 **VS Code**를 **GitHub**에 연결해 볼 거야. 
  - **Figma**는 디자인 도구이고, **VS Code**는 코드를 작성하는 프로그램이야. 이 세 가지를 연결하면 디자인과 코딩 작업을 훨씬 효율적으로 할 수 있어. 
  - **VS Code**에서 **Figma 확장 프로그램**을 설치하고 로그인해 줘. 
  - **Figma**에서는 **개발 모드(Dev Mode)**로 바꾼 다음, **플러그인(Plugins)**에서 'Git'을 검색해서 **GitHub**와 연결해야 해. 
  - **Figma**에서 디자인 요소를 선택하고, **GitHub**에 있는 파일 주소(URL)를 복사해서 붙여넣으면 디자인과 코드가 연결돼. 
  - 마지막으로 **Figma**에서 'Open in VS Code' 버튼을 누르면 **VS Code**에서 바로 코드를 열 수 있어. 

## 3. GitHub** Desktop 앱**으로 코드 변경사항 쉽게 관리하기 
<gen-svg-visual description="A simplified workflow diagram showing how GitHub Desktop streamlines the code update process. It illustrates 'Edit code in VS Code' -> 'GitHub Desktop automatically detects changes' -> '<keyword data-source-id=" />

- 코드를 수정하고 저장하는 과정이 복잡하게 느껴질 수 있는데, **GitHub Desktop 앱**을 쓰면 아주 간단해져. 
  - 원래는 터미널(명령어를 입력하는 창)에서 여러 명령어를 입력해야 하지만, **GitHub Desktop 앱**은 버튼 몇 번만 누르면 돼. 
- **VS Code**에서 코드를 수정하면, **GitHub Desktop 앱**이 자동으로 변경된 부분을 찾아줘. 
  - 예를 들어, 'index.html' 파일의 제목을 '김해지 포트폴리오'로 바꾸면, **GitHub Desktop 앱**에 'HTML 파일이 수정됐다'고 표시돼. 
- 변경된 내용을 확인했으면, **GitHub Desktop 앱**에서 **커밋(Commit)** 버튼을 눌러서 변경 사항을 기록해. 
  - 이때도 어떤 내용을 바꿨는지 제목과 설명을 잘 적어주는 게 중요해. 
- 커밋이 끝나면, **푸시(Push)** 버튼을 눌러서 변경된 코드를 **GitHub** 서버에 올려줘. 
  - 이렇게 하면 네 컴퓨터에 있는 코드가 **GitHub** 웹사이트에도 똑같이 반영되는 거야. 

## 4. **GitHub**에서 변경사항 확인하고 Figma와 VS Code 활용하기 


- 네가 수정한 코드가 **GitHub**에 잘 올라갔는지 확인하려면, **GitHub** 웹사이트의 '액션(Actions)' 탭을 보면 돼. 
  - 여기에 초록색 체크 표시가 뜨면 코드가 성공적으로 반영된 거야. 
- GitHub Pages로 만든 웹사이트에서도 변경된 내용을 바로 확인할 수 있어. 
  - **Figma**에서도 네가 수정한 코드가 디자인에 바로 적용된 걸 볼 수 있을 거야. 
  - 이렇게 **GitHub**, **Figma**, **VS Code** 세 가지 도구가 서로 연결되어 실시간으로 작업 내용을 공유하는 거지. 
- **Figma**와 **VS Code**를 함께 쓰면 디자인과 코딩 작업을 훨씬 편하게 할 수 있어. 
  - **Figma**에서 디자인 요소를 선택하면, **VS Code**에서 해당 디자인의 코드(CSS)를 바로 볼 수 있어. 
  - 그림자나 그라데이션 같은 복잡한 스타일도 코드를 복사해서 붙여넣기만 하면 쉽게 적용할 수 있지. 
  - 특히, **Figma**는 픽셀 단위를 **RM 단위**로 자동으로 바꿔주는 기능도 있어서 반응형 웹 디자인(다양한 화면 크기에 맞춰 디자인이 자동으로 변하는 것)을 만들 때 아주 유용해. 
- 나중에 네가 만든 프로젝트를 다른 사람에게 보여줄 때는 **GitHub 저장소 주소**나 **GitHub Pages 웹사이트 주소**를 보내주면 돼. 
  - 이렇게 하면 상대방이 네 코드를 직접 다운로드하지 않고도 바로 확인하고 수정할 수 있어서 아주 편리해. 
