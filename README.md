# 처음 시작하는 HTML & CSS
## 개발환경 설정
### 웹 브라우저 
 * 크롬  [다운로드](https://www.google.co.kr/chrome/index.html)
 * 파이어폭스  [다운로드](https://www.mozilla.org/ko/firefox/new/)
 ----------------------------------------------------------------
 ### 확장 프로그램
   * Web developer
   * Headingsmap
   * OpenWAX
   -------------------------------------------------------------
   ### 에디터 및 확장 프로그램
   * Visual Studio Code [다운로드](https://code.visualstudio.com)
   * Live Server
   * Prettier-Code Formatter
   * Auto Rename Tag
   * HTML Snippets
   * vscode-icons
   * Monokai-Contrast Theme
   * Markdown Preview Enhanced 
   -------------------------------------------------------------
   ### Git, Github
   * Git [다운로드](https://git-scm.com/downloads)
   * Git [가입하기](https://github.com/)
   * 누구나 쉽게 이해할 수 있는 Git 입문[Git 입문](https://backlog.com/git-tutorial/kr/)
 -------------------------------------------------------------
   ### 웹표준과 웹접근성  
    웹표준이란 
    웹에서 사용되는 표준적인 기술을 의미하며 구조 설계를 위한 HTML, 디자인 및 표현을 위한 CSS, 제어 및 동작을 위한 Javascript가 있다. 
      
    웹접근성이란  
    장애와 비장애에 구애받지 않고 누구나 접근할 수 있도록 하는 개념을 의미한다.
 ------------------------------------------------------------
 ### HTML 명령어  
 #### HTML 기본 구조  
 ```html
<!doctype html>
<html lang="ko-KR">
 <head>
   <title>처음 시작하는 HTML5과 CSS</title>
    </head>
    <body>

    </body>
</html>
```

 #### Git 참조 명령어
    * git status
    * git add . 
    * git cummit -m '0000'
    * git push origin master 
    
  

### 텍스트 관련 요소
 **제목 요소**  
    > h1, h2 등 제목의 의미를 가지는 콘텐츠를 마크 업할때 사용할 수 있습니다. 
 **단락 요소**  
    > P 요소를 사용할 수 있으면, 문단 혹은 단락의 의미를 가집니다.
 **축약어**  
    > abbr 요소를 사용하여 마크업 합니다. 
    이때 abbr 요소는 줄임말 등 단축된 단어로 구성된 콘텐츠를 마크 업 할 때 사용하며,
    title 속성을 사용하여 원래 의미를 표현할 수 있습니다. 

### 목록 관련 요소
 **비순서형 목록**
    > 목록 형식의 콘텐츠 중에서 순서가 상관 없는 경우
    사용할 수 있는 요소로 UL 요소를 사용할 수 있습니다.
    이때, 자식 요소로는 li 요소만 올 수 있습니다. 
 **순서형 목록**
    >목록 형식의 콘텐츠 중에서 순서가 중요한 경우 사용할 수 있는 요소로,
    ol요소를 사용할 수 있습니다. 이때, 자식 요소로는 li 요소만 올 수 있습니다.
 **정의형 목록**
    > 용어 등을 정의할 때 사용하며, 용어 제목은 dt 요소로 용어 설명은 dd 요소로 마크업 할 수 있으며, 정의형 목록 영역임을 알 수 있도록 dl 태그를 상위에 사용합니다.
###하이퍼 링크 및 이미지 요소
 **하이퍼 링크**
    > a 요소를 사용해서 마크업 합니다. 
    이때 a 요소 안에 텍스트나 이미지 등에 링크 기능을 부여할 때 사용할 수 있으며,
    링크의 목적지를 명시하고자 할 때 href 속성에 연결하고자 하는 
    URL이나 File 명을 지정할 수 있습니다. 
 **이미지**
  > img 요소를 사용하고 src 속성에 이미지 파일의 URL이나 파일명을 지정합니다.
  ```html
  <img src="./asset/snowman.png" alt="눈내리는 풍경과 눈사람"
  width="450" height="300">
  ```
  ![멀티캠퍼스]
  (http://el.multicampus.com/landing/images/2016/common/logo.gif)




