리파지토리를 온라인에 올리기
## Github 가입하기
Git은 분산형 버전 관리 프로그램, Github는 온라인에 저장하기위한 Git과 별개의 서비스
## Github에 repository를 생성하기
## 보안 접속을 위한 토큰을 생성
settings->Developer settings->Personal access tokens->Tokens(classic)->Generate new token
## 보안 토큰에 대한 설정하기
통합 자원 식별자로 접근하기
## 보안 토큰은 생성 최초에만 확인할 수 있음
## git에 원격 저장소 주소 설정하기
git remote add origin [원격 저장소 주소]
git remote -v
fetch는 받아오는거 push는 올리는거
git push -u origin main
## 원격저장소 주소가 잘못되었다면 수정하는 방법
git remote set-url origin [올바른 주소]

## 앞으로 우리가 할 루틴
git status
git add .
git status
git commit -m "메시지"
git push origin





