### 로컬저장소

- Repository 생성 : `git init`

- 변경사항 stage 에 추가 : `git add { 파일이름 | . }`

- 변경사항 commit : `git commit -m "{commit message}"`

- git 상태 확인 : `git status`

- git 커밋 로그 확인 : `git log [--oneline]`

- 로컬 저장소에 원격저장소 연결 : `git remote add {저장소이름} {원격저장소url}`

        ex) `git remote add origin https://lab.ssafy.com/s12/d02/gumi02.git`

        **단, 원격저장소는 비어있어야 한다.**

### 원격저장소

- 원격 저장소 로컬 컴퓨터에 복사 : `git clone {원격저장소 url} .`

- 원격 저장소 업데이트 내용 로컬 컴퓨터로 당겨오기 : 
  
  `git pull {원격저장소이름} {브랜치 이름}`  ex) `git pull origin master`

- 로컬 컴퓨터 업데이트 내용 원격저장소로 업로드 :  
  
  `git push {원격저장소이름} {브랜치 이름}`  ex) `git push origin master`






