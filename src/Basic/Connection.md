    <초기 프로젝트 생성 기준>
1. 로컬에서 작업 --> Git Repository에 올릴 때

   순서
   ├─ git init
   ├─ git remote add origin (주소 등록)
   ├─ git add / commit
   └─ git push ──▶ 원격


2. 원격에서 이미 코드가 있을 때 --> 로컬로 받아옴

   순서
   ├─ git clone (주소 등록)
   └─ git remote -v ──▶ 확인

<---------------------------------------------------->

    < SSH로 주소를 등록할 때>
    :(형식) user@host:owner/repository.git

    -> user : git
    -> host : github.com(별칭)
    -> owner : 깃헙 닉네임
    -> repository : 레퍼토리 이름.git
