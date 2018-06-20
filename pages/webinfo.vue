<template>
    <nav class="navbar is-warning">
      <div class="hero-foot">
        <nav class="tabs">
          <div class="container">
            <ul>
              <li>
                <nuxt-link to="/ ">
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

              <li class="is-active">
                <nuxt-link to="/webinfo">
                  <img src="https://image.flaticon.com/icons/svg/788/788893.svg" width="32" height="32">
                  &emsp;
                  WebInfo
                </nuxt-link>
              </li>
            </ul>
          </div>
          <a href="http://www.naver.com" class="navbar-item">
            <img src="https://s3.amazonaws.com/freebiesupply/large/2x/naver-logo-transparent.png" art="logo">
          </a>
          <a href="https://www.google.co.kr" class="navbar-item">
            <img src="https://www.google.co.kr/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" art="logo">
          </a>
        </nav>
        website page
      </div>
    </nav>
</template>