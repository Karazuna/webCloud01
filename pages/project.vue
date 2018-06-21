<template>
<section>
    <div>
      <nav class="navbar is-warning">
        <div class="hero-foot">
          <nav class="tabs">
            <div class="container">
              <ul>
                <li>
                  <nuxt-link to="/">
                    <img src="https://image.flaticon.com/icons/png/512/818/818649.png" width="32" height="32">
                    &emsp;
                    MainPage
                    </nuxt-link>
                </li>

                &emsp;

                <li class="is-active">
                  <nuxt-link to="/project">
                    <img src="https://image.flaticon.com/icons/png/512/856/856018.png" width="32" height="32">
                    &emsp;
                    ProjectList
                  </nuxt-link>
                </li>

                &emsp;

                <li>
                  <nuxt-link to="/webinfo">
                    <img src="https://image.flaticon.com/icons/svg/788/788893.svg" width="32" height="32">
                    &emsp;
                    WebInfo
                  </nuxt-link>
                </li>
              </ul>
            </div>
          </nav>
        </div>
      </nav>
      </div>
      <div align=center>
        <br>
        <a href="https://www.google.co.kr">
              <img src="https://www.google.co.kr/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" width="128" height="128">
            </a> 
      <form method=get action="http://www.google.com/search" target="blank">
        <input type=text name=q size=25 maxlength=255 value="" />
        <input type=submit name=btnG value="Google 검색" />
      </form>
                 
      <br><br>
      <a href="http://www.naver.com" class="item">
              <img src="https://s3.amazonaws.com/freebiesupply/large/2x/naver-logo-transparent.png" width="128" height="128">
            </a>
      <form method=get action="https://search.naver.com/search.naver?" target="blank"> 
        <input type=text name=query size=25 maxlength=255 value="" /> 
        <input type=submit name=btnG value="NAVER 검색" />
      </form> 
      <br>
      </div>

      <article class="message is-primary">
        <div class="message-header">
          <p>4 학년</p>
        </div>
        <div class="message-body">
          <div class="box">
            <p>
              <strong>EYE TOUCH (졸업작품)</strong>
            </p>
            초보 부모를 위한 영유아의 비언어적 표현 해석 도구
            <br>
            <a href="Portfolio/4학년/1. 11_I_4조_정회현+김철언+신중혁+오연중.pdf" target="_blank">개발계획서</a>
            <br>
            <a href="Portfolio/4학년/EYE-TOUCH 융합캡스톤디자인.pdf" target="_blank">PowerPoint</a>
          </div>           
        </div>
      </article>

      <article class="message is-danger">
        <div class="message-header">
          <p>3 학년</p>
        </div>
        <div class="message-body">
          <div class="box">
            <p>
              <strong>EYE TOUCH (졸업연계 설계및 기획)</strong>
            </p>
            초보 부모를 위한 영유아의 비언어적 표현 해석 도구
            <br>
            <a href="Portfolio/3학년/2112 EYE-TOUCH 졸업작품연계 - 개발계획서.pdf" target="_blank">개발계획서</a>
            <br>
            <a href="Portfolio/3학년/2112 EYE-TOUCH 졸업작품연계 - 발표자료.pdf" target="_blank">PowerPoint</a>
            <br>
            <a href="https://www.youtube.com/embed/5bTD0JfJz9w" target="_blank">팀 동영상</a>
          </div>
          <div class="box">
            <p>
              <strong>Sound Connect</strong>
            </p>
            MATLAB을 이용한 음성데이터의 아날로그 신호 통신 모델
            <br>
            <a href="Portfolio/3학년/2110 Sound Connect - 결과보고서.pdf" target="_blank">결과보고서</a>
            <br>
            <a href="Portfolio/3학년/2110 Sound Connect - 학술제 판넬.pdf" target="_blank">학술제 판넬</a>
          </div>
          <div class="box">
            <p>
              <strong>스마트 엘리베이터</strong>
            </p>
            적외선센서를 이용한 엘리베이터
            <br>
            <a href="Portfolio/3학년/2107 스마트 엘리베이터 - 보고서.pdf" target="_blank">개발보고서</a>
            <br>
            <a href="Portfolio/3학년/2107 스마트 엘리베이터 - 학술제 판넬.pdf" target="_blank">학술제 판넬</a>
          </div>              
        </div>
      </article>

      <article class="message is-success">
        <div class="message-header">
          <p>2 학년</p>
        </div>
        <div class="message-body">
          <strong>업데이트 준비중</strong>
        </div>
      </article>

      <article class="message is-link">
        <div class="message-header">
          <p>1 학년</p>
        </div>
        <div class="message-body">
          <strong>업데이트 준비중</strong>
        </div>
      </article>

  </section>
</template>