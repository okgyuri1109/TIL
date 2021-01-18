# Today I Learned :hamster:

## 2021/01/18
### < 부스트캠프 Project A-1>
1. portfolio.html
``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>프로젝트 A-1</title>
    <link rel="stylesheet" href="./css/portfolio.css">
</head>
<body>
    <header>
        <div class="header__title">
            <h1>포트폴리오</h1>
        </div>
    </header>

    <div class="nav">
        <div class="nav__ul">
            <div class="nav__li">테이블 요소</div>
            <div class="nav__li">폼 요소</div>
            <div class="nav__li">리스트 요소</div>
        </div>
    </div>

    <div class="section">
        <h2 class="section__title">구성요소</h2>
        <hr class="section__line">
        <div class="section__table">
            <div class="section__table-title"><span>테이블 요소</span></div>
            <div class="section__table-content"><span>콘텐츠 영역</span></div>
        </div>
        <div class="section__table">
            <div class="section__table-title"><span>폼 요소</span></div>
            <div class="section__table-content"><span>콘텐츠 영역</span></div>
        </div>
        <div class="section__table">
            <div class="section__table-title"><span>리스트 요소</span></div>
            <div class="section__table-content"><span>콘텐츠 영역</span></div>
        </div>
    </div>
    <hr class="footer__line">
    <footer>
        <p class="footer__text">주소: 경기도 성남시 분당구, E-MAIL: honggildong@naver.com</p>
        <p class="footer__copyright">Copyright Hong Gil Dong. All Rights Reserved.</p>
    </footer>
</body>
</html>
```

2. portfolio.css
``` css
* {
    margin: 0;
    padding: 0;
    width: 100%;
    box-sizing: border-box;
}

/*****header*****/
header {
    background-color: #000;
}

.header__title {
    max-width: 1080px;
    line-height: 120px;
    margin: 0px auto;
    padding-left: 40px;
}

.header__title h1 {
    color: #fff;
    font-size: 40px;
    font-weight: bold;
    padding-left: 40px;
}

/*****navbar*****/
.nav {
    background-color: #fff;
    
}

.nav__ul {
    display: flex;
    max-width: 1000px;
    margin: 0px auto;
    padding: 40px 40px 0px 40px;
}

.nav__li {
    border: 1px solid #d1d1d1;
    line-height: 33px;
    text-align: center;
    font-size: 16px;
}

.nav__li:nth-child(2) {
    margin: 0px 14px;
}

.nav__li:hover {
    border: #454545;
    font-weight: bold;
}

/*****section*****/
.section {
    max-width: 1000px;
    margin: 0 auto;
    padding: 40px;
}

.section__title {
    font-size: 20px;
    color: #000;
    font-weight: bold;
    padding-bottom: 20px;
}

.section__line {
    border: 1px solid #454545;
}

.section__table {
    margin-top: 30px;
}

.section__table-title {
    border: 1px solid #d1d1d1;
    background: #f7f7f7;
    line-height: 46px;
    font-size: 16px;
    color: #333;
    font-weight: bold;
    padding-left: 15px;
}

.section__table-content {
    border: 1px solid #d1d1d1;
    border-top: none;
    background: #fff;
    line-height: 60px;
    font-size: 12px;
    color: #000;
    font-weight: bold;
    padding: 30px;
}

.footer__line {
    border: 1px solid #d1d1d1;
}

footer {
    max-width: 1080px;
    margin: 0 auto;
    padding: 40px;
}

.footer__text {
    text-align: center;
    font-size: 12px;
    color: #999;
}

.footer__copyright {
    text-align: center;
    font-size: 12px;
    color: #000;
}
```

## 2021/01/16
### < My FirstMap >
1. nodemone을 사용하여 웹서버 실행하기

2. 네이버 API를 통해 지도서비스를 웹페이지에 띄우기

3. 기본적인 웹페이지 구성하기
    * 지도에 css적용하기
    * 상단메뉴 만들기 (navbar)

3. 지도 위에 마커 구현하기
    * 인포박스를 만든다.
    * 마커 생성하기 및 마커에 css적용한다.
    * data.js 파일에 여러개의 데이터를 입력하여 데이터 파일을 따로 분리한다.
    * index.ejs 파일에 다음 코드를 작성하여 마커에 데이터를 삽입한다.
    
4. 마커 이벤트 처리하기
    * infowindow를 생성하여 클릭 이벤트를 추가한다.
    

5. 지도 클릭 이벤트 설정하기
    * 클릭 이벤트를 구현한다.

6. 현재 위치를 지도 위에 표시하는 기능 만들기
    * 현재 위치 버튼을 만든 후 버튼을 눌렀을 때 현재 위치를 표시하는 기능을 구현한다.
         -> jquery적용
    * 버튼을 눌렀을 때 현재 위치로 화면을 옮기고 zoom in 기능을 구현한다.

7. 현재 위치에 표시되는 마커 수정하기
    * 마커에 애니메이션 효과 주기
        * css파일에서 bow-shadow 기능을 사용하여 효과를 준다.
        * 현재 위치 버튼을 계속 누르게 되면 마커가 계속 생성되는 문제를 수정한다.

## 2021/01/14
* git 사용법
