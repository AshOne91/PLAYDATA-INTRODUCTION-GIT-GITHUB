## 특정 버전의 특정 파일 내용 확인
git show <버전>:<파일 경로>
git show master:src/main.js
특정 커밋 확인시 해당 커밋의 해시 사용
git show abc123:src/index.html

## git에서 변경된 내용 비교
- git diff:현재 작업 트리와 스테이징 영역 사이 비교
- git diff --staged:스테이징 영역과 최신 커밋 사이의 변경내용 확인
- git diff <commit-hash>:현재의 작업 트리와 커밋 사이의 변경 내용 확인

git push origin


