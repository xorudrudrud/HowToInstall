## 원격저장소의 모든 브랜치를 로컬로 다운로드 하는 것
## 다운로드 후 다시 원격으로 push
:cactus::cactus::zap: :whale2:
1. git clone https://github.com/PhoebeYoon/HowToInstall.git
2. ls 
3. cd HowToInstall
4. git branch -a  ( 브랜치의 모든 이름이 보이지는 확인한다. 빨간색으로 표시된다 )
5. /HowToInstall /main/ git checkout git_mac_install  (git_mac_install 브랜치로 이동 )
6. /HowToInstall/git_mac_install / ls -l  ( 내용확인)
7. /HowToInstall /git_mac_install / code .  ( vs code 실행 한 후 README.md 파일 수정한다)
8. /HowToInstall /git_mac_install / git add README.md
9. /HowToInstall /git_mac_install / git commit -m "from local after clone"
10. /HowToInstall /git_mac_install / git push

 :sunny:원격저장소를 확인해 본다 
:rose: 위의 실습에서는 'git_mac_install' 브랜치의 마지막줄에 변경된 내용이 위의 실습을 통해 만들어진것이다
