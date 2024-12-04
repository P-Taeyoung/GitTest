# Git and Github
-----
## Git 사용이유
### 버전관리를 용이하게 하기 위해서

-----

### 터미널 Git 사용
- Github에 ssh key 등록을 해야 github 사용 가능 (ssh로 파일을 가져올 때) 
[.터미널 사용 ssh key 만들기](https://bit.ly/368zxvR)
- git init을 통해 git 초기화 => 해당 프로젝트를 git으로 관리한다는 것을 선언
- .git 파일을 삭제하면 git으로 관리안한다는 의미 rm -rf .git
- git add, git status, git commit -m"메세지" 와 같은 명령어를 통해 Working Directory, Staging Area, Local Repository, Github Repository를 왔다갔다 하면서 관리 가능

### gitignore
- git에 등록되지 않는 파일들 목록 저장 -> .gitignore에 목록에 포함되면 git에 커밋될때 자동으로 제외됨.
- 아래 사이트에 접속하면 파일들에 따라 .gitignore 파일 목록을 추천해서 자동으로 작성해줌.
[.gitignore 작성에 유용한 사이트](https://gitignore.io)

### 기본동작원리
- Working Directory : 작업하는 파일이 있는 디렉토리
- Staging Area : Git에 커밋할 파일들이 올라가있는 영역
- Local Repository : 로컬 git 프로젝트 저장
(위 단계까지는 컴퓨터에 저장됨)

- Remote Repository : 온라인 상의 저장소 

### SourceTree
- SourceTree 프로그램을 이용하여 GUI로 쉽게 Gihhub관리 가능

### Branch 
- 