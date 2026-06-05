
Vscode와 DeskApp을 동시에 사용하면 왜 오류가 날까? 두 프로그램을 같이 쓰면 커밋**(**코드 저장**)** 과정에서 충돌이 생겨 오류가 나기 때문에, 둘 중 하나만 사용해야 해.
## 1. 코드 저장 (커밋) 도구는 하나만 써야 해 
<gen-svg-visual description="A diagram showing two paths for committing code: one from VS Code and one from DeskApp. Both paths lead to a 'Commit' action, but if both are used simultaneously, they lead to a 'Conflict/Error' box. Below the error box, there's a solution: 'Choose one tool only'. This illustrates that using both tools at once causes issues." />

- 코드를 저장하는 작업(커밋)을 할 때, 비주얼 스튜디오 코드 (Vscode)와 데스크앱 (DeskApp)을 동시에 사용하면 안 돼 
  - 마치 두 사람이 동시에 같은 문서를 수정하면 내용이 꼬이는 것과 같아.
  - 둘 중 하나만 사용해야 오류가 생기지 않아 
- 만약 동시에 사용해서 오류가 나면, 비주얼 스튜디오 코드에서 다시 저장하는 명령(재커밋)을 입력해야 해 

## 2. **데스크앱**으로 코드 저장하기 


- **데스크앱**에서 변경된 파일들을 확인하고 저장할 수 있어 
  - 변경된 내용에 대한 제목과 설명을 입력해 
  - 예시: "2일차 수업 완료" (제목), "HTML 속성, CSS 선택자 완료" (설명)
  - **저장** (커밋) 버튼을 누르고, 변경 내용을 서버에 올리는 푸시 오리진 (Push Origin) 버튼을 눌러야 해 
  - 이렇게 하면 네가 작업한 코드가 깃허브 (GitHub)라는 온라인 저장소에 안전하게 올라가는 거야.

## 3. **깃허브 **페이지 확인하기 
<gen-svg-visual description="A flowchart showing the steps to check a GitHub Page. It starts with 'Check GitHub Page'. The first step is 'Actions' (spinning green icon), then 'Settings', then 'Pages'. If a '404 error' occurs, it points to 'Missing index.html file' as the cause, indicating that the main starting file is not present." />

- 코드를 올린 후, 네 작업물이 웹사이트처럼 보이는지 확인하려면 **깃허브 페이지**를 봐야 해 
  - **깃허브**에서 액션 (Actions) 탭을 클릭해 
  - 초록색 동그라미가 다 돌아갈 때까지 기다려야 해 
  - 그다음 설정 (Settings) 탭으로 들어가서 **페이지** (Pages) 메뉴를 찾아 
  - 여기서 네 웹사이트 주소를 클릭했을 때 404 오류 (페이지를 찾을 수 없음)가 뜨면 안 돼 
  - 404 오류가 뜨는 이유는 보통 index.html이라는 시작 파일이 없기 때문이야 
  - 웹사이트는 보통 index.html이라는 파일을 가장 먼저 보여주도록 약속되어 있어. 이 파일이 없으면 웹사이트가 뭘 보여줘야 할지 몰라서 오류가 나는 거야.

## 4. 깃허브를 사용하는 진짜 이유: 코드 보관 
<gen-svg-visual description="A comparison diagram showing two methods of code management. On the left, 'Old Way (Manual)' shows a cycle: 'Code on PC' -> 'Upload to Drive' -> 'Download & Unzip' -> 'Open in <keyword data-source-id=" />

- 지금 당장 웹사이트가 잘 뜨지 않아도 괜찮아 
  - **깃허브**를 사용하는 가장 중요한 목적은 **코드를 안전하게 보관하고 관리하는 연습**을 하는 거야 
- 예전에는 코드를 옮기려면 USB나 클라우드 드라이브에 올리고, 다시 다운로드해서 압축 풀고, 또 다시 올리는 등 복잡했어 
  - **깃허브**를 사용하면 이런 번거로움 없이 코드를 쉽게 저장하고 어디서든 꺼내 쓸 수 있어 
  - 마치 중요한 물건을 은행 금고에 맡겨두는 것처럼, 네 코드를 안전하게 보관하는 곳이라고 생각하면 돼.
