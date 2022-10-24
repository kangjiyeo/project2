### 깃폴더 최초생성
#### git init
### 깃 최초생성시 사용자등록
#### git config --global user.name "qwerewqwerew"
#### git config --global user.email "qwerew0@gmail.com"

----
### git 스테이지 에어리어에 파일등록
#### git add .
### 깃 버전생성 메시지는 "first commit"
#### git commit -m "first commit"
### 깃 브랜치 명 변경(최초 한번 실행-> 브랜치명 변경)
#### git branch -M main
### 깃 원격저장소 연결(최초 한번 실행)
#### git remote add origin https://github.com/qwerewqwerew/git01.git
### 깃 버전을 원격저장소로 업로드
#### git push -u origin main