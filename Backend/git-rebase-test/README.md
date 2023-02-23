## Git Command

- `git init : 위치한 directory에 local storage(저장소)를 만들어 remote storage의 git 과 연결하기 위한 명령어 `
- `git remote add origin <remote repository url> : git init한 directory에 <remote repository url>의 원격저장소와 local을 연결해주는 명령어`
- `git add <file name> :  working directory에서 수정사항이 존재하는 파일에 대하여 변경사항을 staging영역에 추가하는 명령어`
- `git commit : git add 한 파일 또는 파일들에 staging영역에서 어떠한 변경사항이 있었는지 기록하는 명령어`
- `git push origin <branch name> : git commit한 파일 또는 파일들(brnach name)이 작업한 내용을 remote storage(github)에 업로드하는 명령어`
- `git pull origin <branch name> : branch name에서 작업한 내용을 local git에 다운로드하는 명령어`
- `git merge <branch name> : branch name의 작업한 내용을 현재 위치의 branch에 merge(병합)하는 명령어`
