    <초기 프로젝트 생성 기준>
1. 로컬에서 작업 --> Git Repository에 올릴 때

   순서
   1) git init
   2) git remote add origin (주소 등록)
   3) git add / commit
   4) git push ──▶ 원격


2. 원격에서 이미 코드가 있을 때 --> 로컬로 받아옴

    순서
    1) git clone (주소 등록)
    2) git remote -v ──▶ 확인


--------------------------------------------------------

    < SSH로 주소를 등록할 때>
    :(형식) user@host:owner/repository.git

    1) user : git
    2) host : github.com(별칭)
    3) owner : 깃헙 닉네임
    4) repository : 레퍼토리 이름.git
