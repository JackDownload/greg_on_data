<template>
  <footer>
      <div class="container-fluid">
        <div class="row middle-xs">
            <div class="col-xs-4 center-xs middle-xs">
              <div class="box">
                <span class="copyright-text">&#169; gms64</span>
              </div>
            </div>
            <div class="col-xs-4 center-xs middle-xs">
              <div class="box">
                <span class="footer-link">
                  <a href="https://github.com/gms64" aria-label="Github" target="_blank">
                    <img class="icon-filter" style="color:#fff;" height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" alt="Github"/>
                  </a>
                </span>
                &nbsp;&nbsp;
                <span class="footer-link">
                  <a href="https://twitter.com/greg_on_data" aria-label="Twitter" target="_blank">
                    <img class="icon-filter" style="color:#fff;" height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" alt="Twitter"/>
                  </a>
                </span>
              </div>
            </div>
            <div class="col-xs-4 center-xs middle-xs">
              <div class="box">
                <span class="footer-link"><nuxt-link to="/about">about</nuxt-link></span>&nbsp;&nbsp;
                <span class="footer-link"><nuxt-link to="/contact">contact</nuxt-link></span>
              </div>
            </div>
        </div>
      </div>
  </footer>
</template>