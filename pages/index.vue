<template>
<section>
    <div>
      <nav class="navbar is-warning">
        <div class="hero-foot">
          <nav class="tabs">
            <div class="container">
              <ul>
                <li class="is-active">
                  <nuxt-link to="/">
                    <img src="https://image.flaticon.com/icons/png/512/818/818649.png" width="32" height="32">
                    &emsp;
                    MainPage
                    </nuxt-link>
                </li>

                &emsp;

                <li>
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

 
 <section class="section">
    <div class="container">
      <div align="center">
      <h1 class="title">General Information for Cheol-Eon Kim &emsp;&emsp;&emsp;&emsp;&emsp;<img src="~assets/cheoleon.jpg" align="middle" width="177" height="236"></h1>
      </div>
      <br><br><br>
      <h3 class="subtitle">
        ■ College Student
        <br>
        ■ Mokwon University - Division of Information and Communication Convergence Engineering 2019 Candidate
        <br>
        ■ E-mail : kchy1234@naver.com
        <br><br>
        <strong>[Experiences Programing Language]</strong>
        <br>
        ■ Visual C Language
        <br>
        ■ Microsoft Foundation Classes
        <br>
        ■ Arduino
        <br>
        ■ Android
        <br>
        ■ Node.JS
        <br>
        ■ JSP & PostgreSQL
        <br>
        ■ Vue.JS & Nuxt.JS
      </h3>
    </div>
    
  </section>
  </section>
</template>