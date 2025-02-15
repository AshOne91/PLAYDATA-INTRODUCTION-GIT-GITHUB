## 엽업 시뮬레이션
거부 되었다면
git pull을 먼저 진행

최신화를 위해서 git fetch 명령과 git merge 혹은 두단계 합친 git pull을 실행

git merge origin/main
//충돌이 있었다. 자동 머지가 실패했다. 고치고 이 결과를 커밋하라

## git의 충돌
같은 파일의 동일한 부분을 수정하여 병합시도할 때 발생할 수 있음
수동으로 충돌을 해결해야 함
1. 동일 파일의 동일한 부분 수정
2. 브랜치 병합

충돌이 있는 파일은 git status를 사용했을 때 Unmerged상태로 표시

충돌부분이 기록되어 있음
수동으로 수정진행 하기

## git 충돌 해결하기
1. 충돌 확인 : <<, ==, >>
2. 충돌 해결 : 수동으로
3. 충돌 해결한 파일 스테이징 : git add first.txt
4. git commit -m 블라블라

git push origin
(해결 완료)

git pull origin
fetch는 그냥 받는거고 pull은 head를 최신으로 병합









