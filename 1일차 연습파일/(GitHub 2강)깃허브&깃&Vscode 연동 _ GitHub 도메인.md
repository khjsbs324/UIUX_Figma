​
깃허브**(GitHub)**와 **깃(Git)**, VS Code**(비주얼 스튜디오 코드)**를 어떻게 연동하는 걸까? 깃허브 데스크톱 앱을 통해 깃허브와 VS Code를 연결하고, 깃(Git)을 따로 설치해서 **버전 관리(코드 변경 이력 관리)**를 할 수 있어.
## 1. 웹사이트의 기본 파일 만들기 
<gen-svg-visual description="A simple diagram showing how to create an index.html file. It starts with a text file, then renames it to index.html, emphasizing that 'index.html' is a universal standard for the main webpage file." />

- 웹사이트의 메인 페이지는 항상 index.html이라는 이름으로 만들어야 해 
  - 이건 전 세계적으로 약속된 이름이야. 마치 사과를 '사과'라고 부르기로 약속한 것과 같아 
  - 다른 이름으로 만들면 웹사이트가 제대로 작동하지 않을 수 있어 
- 파일을 만들 때는 다음과 같이 해봐 
  - 새 텍스트 문서를 만들고 
  - 파일 이름을 **index.html**로 바꿔줘 
  - 파일 확장자(.txt)까지 모두 지우고 바꿔야 해 
  - 파일 이름이 바뀌면 컴퓨터가 "이제 이 파일을 메모장으로 못 열 수도 있는데 괜찮아?" 하고 물어볼 거야. 그때 "응, 괜찮아"라고 대답하면 돼 
- 파일이 제대로 만들어지면 크롬(Chrome) 브라우저 모양 아이콘이 뜰 거야 

## 2. 깃허브(GitHub)에 파일 올리기 


- 만든 HTML 파일을 **깃허브(GitHub)**에 올려서 다른 사람들과 공유하거나 웹사이트로 만들 수 있어 
- 파일을 올리는 방법은 간단해 
  - HTML 파일을 마우스로 끌어서 깃허브 웹페이지에 있는 저장소(repository)에 넣어줘 
  - 그다음 아래쪽에 있는 **'**Commit** changes'** 버튼을 눌러주면 파일이 올라갈 거야 

## 3. 깃허브 데스크톱(GitHub Desktop) 설치 및 연동 
<gen-svg-visual description="A flowchart showing the steps to install GitHub Desktop and connect it to a GitHub account. It starts with opening 'Code' on GitHub, selecting 'Open with GitHub Desktop', downloading and installing the application, then logging in and authorizing through the GitHub website." />

- **깃허브 데스크톱(GitHub Desktop)**은 깃허브를 더 쉽게 사용할 수 있게 도와주는 프로그램이야 
  - 깃허브 웹사이트에서 **'Code'** 버튼을 누르고 **'Open with GitHub Desktop'**을 선택하면 다운로드 페이지로 이동해 
  - **'Download for Windows'** (또는 Mac) 버튼을 눌러서 프로그램을 다운로드하고 설치해 줘 
  - 설치가 끝나면 깃허브 웹사이트에서 로그인하고 **'연결'** 버튼을 눌러서 깃허브 계정과 연결하면 돼 
  - 이 프로그램은 고양이와 문어를 합친 모양의 아이콘을 가지고 있어 
- 깃허브 데스크톱을 설치하면 컴퓨터에 있는 파일을 깃허브와 쉽게 주고받을 수 있어 
  - 설치 후에는 아까 만든 저장소(repository)를 선택해서 열어줘 
  - 만약 더블 클릭이 안 되면, 화면에 보이는 파란색 버튼을 찾아 눌러주면 돼 

## 4. VS Code(비주얼 스튜디오 코드)와 깃허브 데스크톱 연결 


- **VS Code(비주얼 스튜디오 코드)**는 코드를 작성하는 프로그램인데, 깃허브 데스크톱과 연결해서 사용하면 아주 편리해 
  - 깃허브 데스크톱 화면에서 **'Open with Visual Studio Code'** 버튼을 누르면 VS Code가 자동으로 열릴 거야 
  - 이렇게 연결하면 VS Code에서 코드를 수정하고 바로 깃허브에 올릴 수 있어 

## 5. 깃(Git) 설치하기 
<gen-svg-visual description="A step-by-step guide on how to install Git. It shows navigating to the Git website, clicking 'Downloads', then 'Windows' (or other OS), and finally selecting 'Download GUI' to get the installer. It emphasizes that Git is a separate tool from GitHub." />

- **깃(Git)**은 코드의 변경 이력을 관리해 주는 도구야. 깃허브(GitHub)와는 다른 프로그램이야 
  - VS Code에서 깃이 설치되어 있지 않다고 팝업이 뜰 수도 있어 
  - 깃을 설치하려면 인터넷 검색창에 **'Git'**이라고 검색해서 공식 웹사이트로 들어가 
  - 웹사이트에서 **'Downloads'**를 누르고, 사용하는 운영체제(윈도우, 맥 등)에 맞는 버전을 선택해서 다운로드하고 설치해 줘 
  - 깃 설치가 끝나면 VS Code를 껐다가 다시 켜는 게 좋아 

## 6. VS Code에서 HTML 파일 수정 및 깃허브에 반영하기 


- VS Code에서 HTML 파일을 열고 내용을 수정할 수 있어 
  - 예를 들어, <body> 태그 안에 **"안녕하세요"**라고 입력해 봐 
  - 코드를 수정하면 파일 이름 옆에 동그라미나 **'M'** 표시가 나타날 거야. 이건 아직 저장되지 않았거나 변경되었다는 뜻이야 
  - **Ctrl + S**를 눌러서 저장하면 동그라미 표시가 사라질 거야 
- 수정한 내용을 깃허브에 올리려면 다음 단계를 따라야 해 
  - VS Code 왼쪽 메뉴에서 **'소스 제어(Source Control)'** 아이콘(연결 공유 아이콘처럼 생긴 것)을 눌러 
  - 변경된 HTML 파일이 보일 거야. 만약 안 보이면 **'+'** 버튼을 눌러줘 
  - **'**커밋 메시지**(Commit message)'**를 작성해. 이건 어떤 내용을 변경했는지 기록하는 메모 같은 거야 
  - 나중에 다른 사람들과 함께 작업할 때 누가 어떤 부분을 수정했는지 알 수 있어서 아주 중요해 
  - 파란색 **'Commit'** 버튼을 누르고, 또 한 번 파란색 버튼을 눌러서 변경 사항을 깃허브에 올려줘 
  - 이때 "다시는 물어보지 않겠다"는 옵션을 선택하면 다음부터는 자동으로 올라갈 거야 

## 7. 깃허브에 변경 사항 반영 확인하기 
<gen-svg-visual description="A sequence diagram showing how to check the status of changes pushed to GitHub. It illustrates navigating to the GitHub repository, clicking 'Actions', and observing the progress of the deployment. It also shows the 'Push origin' step in GitHub Desktop and how a green checkmark indicates successful deployment to the live site." />

- VS Code에서 변경 사항을 올렸다고 바로 웹사이트에 적용되는 건 아니야 
  - 깃허브 웹사이트로 가서 **'**Actions**'** 탭을 눌러봐 
  - 여기에 변경 사항이 깃허브에 반영되는 과정이 보일 거야. 노란색 동그라미가 초록색 체크 표시로 바뀌면 성공적으로 반영된 거야 
  - 깃허브 데스크톱에서도 **'**Push origin**'** 버튼을 눌러서 변경 사항을 완전히 올려줘야 해 
- 웹사이트에 접속해서 변경된 내용을 확인할 수 있어 
  - 깃허브 저장소 페이지에서 **'Settings'**를 누르고 **'**Pages**'**를 선택해 
  - **'View deployment'** 또는 **'Visit site'** 버튼을 누르면 웹사이트 주소가 나올 거야 
  - 이 주소로 들어가서 새로고침을 하면 아까 입력했던 **"안녕하세요"**라는 글자가 보일 거야 
  - 이 과정이 완료되면 깃허브와 VS Code가 성공적으로 연동된 거야 
