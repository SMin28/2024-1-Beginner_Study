## 1주차 학습 내용

# git을 사용하는 이유
코드 수정 관리
파일 관리
협업
버전 관리

# git의 영역
Working Directory
Staging Area
Repository

# git으로 파일 관리하기
디렉토리에 Git 저장소를 만들기: git init
Git으로 관리할 대상 등록하기: git add
파일 수정 후 로컬 저장소로 옮기기: git commit

# 커밋하는 이유
무엇을 수정했는지 명시해야 한다

# GitHub에 올리기에 앞서
$git remote add origin <주소>
$git branch -M main
$git push -u origin main

# GitHub에 올리기
$git add <파일명>
$git commit -m "<commit message>"
$git push origin main