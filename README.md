22300783 / 하서희

hw02수행내용_

이번 과제에서는 HTML과 CSS를 적극 활용하였다.
동일한 HTML 콘텐츠에 서로 다른 스타일을 적용하는 웹페이지를 제작하고,
Bootstrap을 활용한 로그인 페이지도 구현하였다.

각 페이지 설명_

1. index.html_
과제에 사용되는 각 페이지로 이동할 수 있는 메인 페이지이다.
No Style, Style 1, Style 2, Bootstrap Example 페이지로 연결된다.
URL: https://oss-personal2.vercel.app/index.html

2. nostyle.html_
기본 HTML의 뼈대만 있는 페이지이다. PPT 문법을 사용하여
AI의 도움없이 구현할 수 있었다. 
URL: https://oss-personal2.vercel.app/nostyle.html

3. style1.html_
CSS를 적용하여 상단 영역, 메뉴, 본문, 사이드바,
하단 영역으로 구성된 레이아웃을 구현하였다.
AI를 이용하여 화면 크기에 따라 레이아웃이 변경되도록 반응형 CSS도 적용하였다.
이는 교수님 ppt에 나와있지 않은 내용이라 공부가 되었다.
URL: https://oss-personal2.vercel.app/style1.html

4. style2.html_
Style 1과 다른 CSS 스타일을 적용하여 다른 형태로 보이도록 구성했다.
페이지 검사 탭을 이용해 CSS 부분을 자세히 들여다 보았다.
URL: https://oss-personal2.vercel.app/style2.html

5. bootstrap_ex.html_
Bootstrap CSS를 활용하여 로그인 페이지를 제작하였다.
이메일과 비밀번호 입력, Remember me, Sign in 버튼을 구현하였다.
ight / Dark / Auto 테마를 선택할 수 있도록 추가 기능도 구현하였다.
Bootstrap CSS 파일을 <link>로 연결하여 사용하였다.
URL: https://oss-personal2.vercel.app/bootstrap_ex.html

Vercel deploy URL_https://oss-personal2.vercel.app/

Weekly review_
HTML을 이용하여 제목, 문단, 목록, 링크 등 페이지 레이아웃을 구성하는 방법을 배웠다.
SS를 이용하여 글자 색상, 배경색, 여백, 크기, 위치 등을 변경하고 HTML의 레이아웃을 구성하는 방법을 배웠다.
Bootstrap을 사용하면 기본적인 스타일과 UI를 직접 처음부터 작성하지 않아도
빠르게 웹페이지를 구성할 수 있다는 것을 알게 되었다.

html vs css_
HTML은 웹페이지에 무엇을 보여줄지와 구조를 만드는 역할을 한다.
스트럭쳐 느낌이 매우 강하다.
제목, 문단, 목록, 버튼, 링크 등의 콘텐츠를 HTML 태그로 구성할 수 있다.
CSS는 HTML로 만들어진 요소가 어떻게 보일지를 결정하는 역할을 한다.
글자 색상, 배경색, 크기, 여백, 정렬, 레이아웃 등을 디자인 할 수 있다.
요약하면 html은 뼈대 만들기, css는 그 뼈대 위를 채우는 살 역할을 한다고 보면 된다.

Bootstrap 사용법_
Bootstrap은 웹페이지를 빠르고 편리하게 디자인할 수 있도록 미리 만들어진 CSS가 있다.
기본적인 디자인을 일일히 css로 작성하지 않아도 된다. -> 시간절약, 효율성 향상
이번 과제에서는 HTML의 <head> 부분에서 Bootstrap CSS 파일을 참고하여 사용하였다.
Bootstrap을 사용하면 웹페이지를 비교적 빠르게 제작할 수 있고,
일정하게 디자인을 적용할 수 있다는 장점이 있다.

Problem & solution_
본격적으로 웹페이지를 제작하자니, 뼈대는 만들 수 있었지만
특정 페이지의 디자인을 똑같이 따라하는 것이 매우 어려웠다.
페이지의 검사기능 없이는 페이지를 만들 수 없을 정도로 헷갈렸다.
이 문제는 전부 CSS 부분이어서, AI를 사용하여 해당 페이지의 코드를 분석한 다음
구현하는 것이 매우 큰 도움이 되었다. AI 요약 기능도 적극 활용하였다.

AI usage_
뼈대를 제외한 전반적인 디자인 코드를 AI를 통해 작성하였다.
AI가 생성하거나 제안한 코드를 그대로 사용하기보다는
직접 코드를 확인하면서 HTML 태그의 구조와 href 속성, 
CSS 선택자 및 스타일이 실제로 어떤 역할을 하는지 확인하였다.
코드의 형식도 내 스타일에 맞추어서 일일히 수정하였고, 보다 편하게 볼 수 있었다.

Reflection_
이번 과제는 웹페이지의 디자인을 어떻게 하면 똑같이 만들지에 대한
본격적인 탐구가 포함되어 있었다. 나만의 디자인은 만들기 쉬웠지만,
정작 다른 페이지의 디자인을 따라 만드려니 매우 막막하였다.
아마 AI가 없었다면 디자인을 비슷하게 만드는 것조차 매우 버거웠을 것이다.
앞으로는 AI의 의지도를 점점 줄이면서 CSS를 사용하는 방법을 익혀야 겠다는 생각이 들었다.
수업시간에 배우지 않은 반응형 코드같은 부분은 내가 직접 분석하고 이해하였는데,
이것은 또다른 배움이 된 것 같아 AI의 도움이 되는 부분을 확실히 체감할 수 있었다.