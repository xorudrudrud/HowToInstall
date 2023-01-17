# 원격저장소의 모든 브랜치를 로컬로 다운로드 하는 것
# 다운로드 후 다시 원격으로 push

- git clone https://github.com/PhoebeYoon/HowToInstall.git
- ls 
- cd HowToInstall
- git branch -a  ( 브랜치의 모든 이름이 보이지는 확인한다. 빨간색으로 표시된다 )

- /HowToInstall /main/ git checkout git_mac_install  (git_mac_install 브랜치로 이동 )
- /HowToInstall/git_mac_install / ls -l  ( 내용확인)
- /HowToInstall /git_mac_install / code .  ( vs code 실행 한 후 README.md 파일 수정한다)
- /HowToInstall /git_mac_install / git add README.md
- /HowToInstall /git_mac_install / git commit -m "from local after clone"
- /HowToInstall /git_mac_install / git push

원격저장소를 확인해 본다 
위의 실습에서는 
