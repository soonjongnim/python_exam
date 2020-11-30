# python 테스트

## ..
 ls -al .ssh

ssh-keygen.exe -t rsa -C "bit_r39"


 cat .ssh/id_rsa.pub
복사하여 깃허브에 넣어준다.

git clone git@github.com:soonjongnim/python_exam.git 깃허브복사하기

cd python_exam/ 해당 폴더로 이동

nano README.md 수정하기

 git status 상태확인

 git diff README.md 수정되었다면 수정내용확인

git add README.md 수정된 파일  추가하기

git commit -m 'readme수정' 컴잇하기

 git diff README.md 수정이되면 안나옴

 git remote -v

git push -u origin main 서버에 올리기
