## Git 브랜치
특정 커밋에 대한 참조에 지나지 않음(커밋을 가르키는 이름)
작은 단위로 잘게 나누어 작업
하나의 커밋과 그 부모 커밋들을 포함하는 작업 내역

## Git 브랜치 활용
1. 새로운 기능 개발
2. 버그 수정
3. 특정 릴리즈 또는 배포
4. 실험적인 작업

## Git 브랜치 조회하기
1. 모든 브랜치 보기 : git branch
2. 원격 브랜치까지 전체 보기 : git branch -a
3. 원격 브랜치만 보기 : git branch -r
4. 브랜치와 마지막 커밋 보기: git branch -v

## 브랜치 생성
git branch <branch-name>

작업시 브랜치는 하나만 선택가능

head를 옮겨야됨
brach를 전환하려면
git checkout <branch-name>

## git 브랜치와 합치기
main 브랜치로부터 feature 브랜치의 변경사항을 가져오려면
git checkout main
git merge feature
feature 브랜치의 변경 사항을 main 브랜치에 병합

## git 브랜치 삭제하기
git branch -d feature
현업시 바로 삭제하지 않는게 좋음








