# Git 명령어 메모

## 새 저장소 생성 및 초기 설정
```bash
# README.md 파일 생성
echo "# BCMWebService" >> README.md

# Git 저장소 초기화
git init

# 파일 스테이징
git add README.md

# 첫 커밋 생성
git commit -m "first commit"

# main 브랜치로 이름 변경
git branch -M main

# 원격 저장소 추가
git remote add origin https://github.com/YoungsikMoon/BCMWebService.git

# 원격 저장소에 푸시
git push -u origin main
```

## 기존 저장소 연결하기
```bash
# 원격 저장소 추가
git remote add origin https://github.com/YoungsikMoon/BCMWebService.git

# main 브랜치로 이름 변경
git branch -M main

# 원격 저장소에 푸시
git push -u origin main
```

## Git 한글 설정
```bash
# 한글 커밋 메시지 인코딩 설정
git config --global i18n.commit.encoding utf-8
```

## 유용한 Git 설정
```bash
# 한글 파일명 깨짐 방지
git config --global core.quotepath false

# 기본 인코딩을 UTF-8로 설정
git config --global core.encoding utf-8

# 커밋 메시지 인코딩 설정
git config --global i18n.commit.encoding utf-8

# 로그 출력 인코딩 설정
git config --global i18n.logoutputencoding utf-8
```