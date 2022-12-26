# 맥에서 프로그램 설치방법 안내

1. https://git-scm.com/download/mac 접속합니다
2. 맥에서 처음설치한다면,
3. 아래 이미지를 찾으세요 <br><img width="338" alt="스크린샷 2022-12-26 오전 11 43 46" src="https://user-images.githubusercontent.com/48478079/209492952-be1522a0-0b1a-4b58-bf68-3ac9ac417a95.png">
4. 우선 , 위의 이미지에 있는 <span style="background-color:#ff000">하늘색의  "Homebrew" </span>를 찾아 클릭하면<br>
<br><img width="200" alt="스크린샷 2022-12-26 오후 12 01 10" src="https://user-images.githubusercontent.com/48478079/209494263-e7c23c44-64c7-4764-b2f8-44f77225f9b7.png"> 
<br> 화면이 보입니다 여기서 한국어를 선택하시면 한글로 설명된 문장들이 나옵니다. "Homebrew 설치하기" 아래쪽에 
```
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)
```
<br> 복사합니다 이것을 맥의 터미널 기능을 이용해서 실행해야 합니다.<br><br>
5. 터미널이란 말을 잘 모르신다면 "vs code" 실행하시고 상단메뉴에 "터미널" > "새터미널"를 선택하세요 ( vs code를 실행한 뒤에 모니터 위쪽에 나타납니다  다른 프로그램이나 브라우저창이 활성화되어 있다면 다른 메뉴가 보일 수 있습니다 ) <br><br>
6. vs code의 터미널 ( 보통 까만색의 바탕에 흰색글자들이 보이면 )에서 <b>"붙여넣기" </b>합니다 <br><br>
7. 여기서 패스워드를 물어보면 컴퓨터 시동할때 입력하는 "비밀번호" 입력합니다 <br><br>
8.``` brew intall git``` 실행합니다. <br><br>
9. 마지막으로 ``` git --version  ``` 엔터를 합니다 결과로  ``` git version 숫자  ``` 가 나오면 완성입니다
