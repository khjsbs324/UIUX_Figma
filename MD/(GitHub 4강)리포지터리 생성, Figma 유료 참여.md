
깃허브(GitHub)와 피그마(Figma)를 연동하는 방법은? 깃허브 데스크톱 앱에서 계정을 확인하고, 리포지토리**(저장소)를 다시 **클론**(복제)하는 과정**을 거쳐야 해. 이렇게 하면 여러 툴을 함께 사용하며 효율적으로 작업할 수 있어.
## 1. 깃허브(GitHub)와 피그마(Figma)를 함께 쓰는 이유 
<gen-svg-visual description="A diagram showing three interconnected circles: 'Figma (Design)', 'GitHub (Code Management)', and 'Visual Studio Code (Coding)'. Arrows connect all three, indicating a workflow where design, code management, and coding are integrated. A central text bubble says 'Seamless Workflow'." />

- 디자인 작업(피그마)과 코딩 작업(비주얼 스튜디오 코드)은 서로 뗄 수 없는 관계야. 
- 그래서 실무에서는 이 세 가지 도구를 한꺼번에 연결해서 사용하면 훨씬 효율적이야. 
  - **피그마(Figma)**: 디자인을 하는 도구
  - **깃허브(GitHub)**: 코드를 저장하고 관리하는 도구 (마치 공동 작업 폴더 같아)
  - **비주얼 스튜디오 코드(Visual Studio Code)**: 코드를 직접 작성하는 도구

## 2. 깃허브에 새 저장소(Repository) 만들고 파일 올리기 

1. 'Go to Sidebar' -> 'All Repositories' 
2. 'Click New Repository' 
3. 'Name Repository (e.g., UIU_Figma)' 
4. 'Click Create Repository' 
5. 'Click New File' 
6. 'Name File (index.html)' 
7. 'Add Example Content (e.g., '2x')' 
8. 'Click Commit Changes' 
9. 'Add Commit Message (e.g., '첫 파일 생성')' 
10. 'Click Commit Changes' 
Each step has an arrow pointing to the next." />

- 깃허브에 새로운 저장소(repository)를 만들어서 파일을 관리할 수 있어. 이건 마치 새로운 프로젝트 폴더를 만드는 것과 같아. 
  - 왼쪽 사이드바에서 'All repositories'를 눌러. 
  - 오른쪽 위에 있는 'New repository' 버튼을 눌러서 새 저장소를 만들어. 
  - 저장소 이름은 'UIU_Figma'처럼 피그마와 함께 쓸 거라는 걸 알 수 있게 지어줘. 
  - 'Create repository' 버튼을 눌러서 저장소를 만들어. 
- 저장소에 첫 파일을 만들어 올리는 과정이야. 
  - 'Add file' 버튼을 누르고 'Create new file'을 선택해. 
  - 파일 이름은 항상 **index.html**로 해줘. 이건 웹사이트의 첫 페이지를 의미하는 약속이야. 
  - 파일 내용에는 간단하게 '2x'라고 입력해봐. 
  - 'Commit changes' 버튼을 눌러서 파일을 저장소에 올려. 
  - '첫 파일 생성'이라고 메시지를 남겨서 어떤 변경사항인지 기록해두는 게 좋아. 

## 3. 깃허브 저장소의 브랜치(Branch) 설정하기 
<gen-svg-visual description="A simple diagram showing a 'Settings' icon leading to a 'Pages' menu. Inside 'Pages', there's a dropdown labeled 'Branch' which is changed from 'None' to 'Main'. An arrow points from 'Main' to a 'Save' button, and then to 'Code' indicating the next step." />

- 저장소의 **브랜치(Branch)**는 작업 공간을 나누는 기능이야. 마치 게임에서 여러 세이브 파일을 만들어서 각자 다른 진행 상황을 저장하는 것과 비슷해. 
  - 'Settings' 메뉴로 들어가서 왼쪽에 있는 'Pages'를 눌러. 
  - 'Branch' 설정이 'None'으로 되어 있다면 'Main'으로 바꿔줘. 'Main'은 보통 메인 작업 공간을 의미해. 
  - 'Save' 버튼을 누르고 다시 'Code' 탭으로 돌아와. 

## 4. 깃허브 데스크톱 앱에서 계정 확인 및 저장소 가져오기 

1. Initial state: A login screen or a screen showing a repository that might not be the user's.
2. User clicks 'File' menu.
3. User clicks 'Options' from the dropdown.
4. A settings window appears. User clicks 'Sign Out' button next to their GitHub account.
5. User clicks 'Sign In' button.
6. A browser window opens for GitHub login. User enters credentials and authorizes.
7. The GitHub Desktop app now shows the correct user account.
8. User clicks 'File' menu again.
9. User clicks 'Add' -> 'Clone Repository'.
10. A dialog appears. User can either paste a repository URL or select from a list of their own repositories.
11. User selects their newly created 'UIU_Figma' repository.
12. User clicks 'Clone' button.
13. The app now displays the 'UIU_Figma' repository, confirming it's correctly cloned." />

- 깃허브 데스크톱 앱에서 내 계정으로 로그인되어 있는지 확인하고, 내가 만든 저장소를 가져와야 해. 
  - 앱을 열었을 때 'Clone'이라는 메시지가 뜨면, 지금 보고 있는 저장소가 내가 만든 게 맞는지 확인해야 해. 
  - 만약 다른 사람 계정으로 로그인되어 있다면, 로그아웃하고 내 계정으로 다시 로그인해야 해. 
  - 'File' 메뉴에서 'Options'를 누르고, 로그인된 계정을 'Sign Out' 해줘. 
  - 다시 'Sign In'을 눌러서 내 깃허브 계정으로 로그인해. 
- 계정을 바꿨는데도 저장소가 바뀌지 않았다면, 저장소를 다시 가져와야 해. 
  - 'File' 메뉴에서 'Add'를 누르고 'Clone repository'를 선택해. 
  - 내 깃허브 저장소 링크를 입력하거나, 내 저장소 목록에서 'UIU_Figma'를 선택해서 가져와. 
  - 이렇게 하면 내 계정으로 내 저장소를 제대로 사용할 수 있게 돼. 

## 5. 비주얼 스튜디오 코드(VS Code)와 피그마(Figma) 연동하기 
<gen-svg-visual description="A diagram showing the integration of Visual Studio Code and Figma.<ol><li>'Visual Studio Code' icon.</li><li>An arrow points from VS Code to a 'Plugins/Extensions' icon.</li><li>Inside the Plugins/Extensions section, a search bar shows 'Figma'.</li><li>Below the search bar, a 'Figma' plugin icon is displayed with an 'Install' button.</li><li>After installation, an arrow points to a 'Figma (Paid Version)' icon, indicating that this feature works only with the paid version of Figma.</li><li>Another arrow points to 'Team Project' in Figma, emphasizing that the feature is used within a shared project." />

- 비주얼 스튜디오 코드에서 피그마 디자인을 바로 보면서 코딩할 수 있도록 연동할 거야. 
  - 비주얼 스튜디오 코드를 열어. 
  - 왼쪽에 있는 '확장(Extensions)' 아이콘(네모 4개 모양)을 눌러. 
  - 검색창에 'Figma'라고 검색해서 피그마 플러그인을 설치해. 
- **중요**: 이 기능은 유료 피그마에서만 사용할 수 있어. 
  - 선생님이 제공하는 팀 프로젝트 피그마 파일에서만 이 기능을 쓸 수 있어. 
  - 선생님이 여러분을 팀 프로젝트에 초대할 거야. 메일이나 수업 페이지 링크를 확인해서 참여하면 돼. 

## 6. 피그마 팀 프로젝트 참여 및 권한 설정 


- 선생님이 초대하는 피그마 팀 프로젝트에 참여해야 해. 
  - 선생님이 메일이나 수업 페이지에 올려준 링크를 통해 피그마 팀 프로젝트에 접속해. 
  - '권한 요청' 버튼을 눌러서 팀 프로젝트에 참여할 수 있도록 요청해. 
- 권한이 없거나 신분 인증이 필요할 수 있어. 
  - 만약 권한이 없다고 나오면, 선생님이 'Editor' 권한으로 초대해 줄 거야. 
  - '신분 인증' 메시지가 뜨면, 이전에 받았던 재원 증명서 등으로 인증을 진행해야 해. 
  - 인증이 완료되면 피그마에서 디자인 요소를 만들고 편집할 수 있게 돼. 
