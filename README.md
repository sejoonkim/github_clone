# GitHub clone coding

### HEAD 설정

1. open graph | twitter card

   - ```html
     <meta property="og:type" content="website" />
     ```

     ***

     ```html
     <meta property="twitter:card" content="summary" />
     ```

2) Google Fonts

   - ```html
     <!-- Get less heavy fonts from google fonts -->
     <link
       href="https://fonts.googleapis.com/css?family=Roboto:300,400,500&display=swap"
       rel="stylesheet"
     />
     ```

     ***

     ```css
     body {
       font-family: "Roboto", sans-serif;
       font-size: 100px;
     }
     ```

3. Browser Style Default

   - reset.css cdn

     - ```html
       <link
         rel="stylesheet"
         href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.css"
       />
       ```

### 공통

1. 최상위 요소, BEM

   - BEM, CSS 작명규칙

     - \_\_ : ~의 일부분이다

       -- : ~의 상태

       -: 띄어쓰기 대체

     - ```html
       <div class="container">
         <div class="container__item"></div>
       </div>

       btn success btn danger btn warning
       <div class="btn--success"></div>
       <div class="btn--danger"></div>
       <div class="btn--warning"></div>

       toggle-btn
       <div class="toggle-btn"></div>
       ```

2) 전역 스타일 - 버튼

   - 반복되는 스타일을 미리 정의하자 -> [codepen.io](https://codepen.io)

   - 가상요소 ::before :: after
     - :: before - 해당 태그 앞, ::after - 해당 태그 뒤
   - 선 CSS 전역설정 -> 후 html 요소에 적용도 가능하다.
