<template>
  <div>
    <section class="app-downloading-wrapper">
      <div
        class="downloading-frame d-flex justify-content-center align-items-center"
      >
        <b-container>
          <b-row>
            <b-col cols="12">
              <h2>
                Ready? Download the showcase app now or test our IVR Call Centre
              </h2>
              <p>
                Be the innovator in your market. Experience how mobile
                biometrics can be used to facilitate seamless payments.
              </p>
              <ul>
                <li>
                  <a href="#">
                    <img
                      src="../../assets/images/ios.svg"
                      class="img-fluid"
                      alt=""
                  /></a>
                </li>
                <li>
                  <a href="#">
                    <img
                      src="../../assets/images/google.svg"
                      class="img-fluid"
                      alt=""
                  /></a>
                </li>
              </ul>
            </b-col>
          </b-row>
        </b-container>
      </div>
    </section>
    <div class="new-case-wrapper w-100 ">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="news-frame bg-1">
              <div
                class="news-head d-flex  justify-content-md-between align-items-center"
              >
                <div class="newscase-headline">
                  <h2>Request a new use case</h2>
                  <p>
                    Can’t find your specific use case? Our team can support you
                    in the assessment of new use cases.
                  </p>
                </div>
                <div class="newscase-btn">
                  <a href="#" class="btn-newscase">Request Now</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <footer>
      <div class="footer-wrapper footer-bg">
        <b-container>
          <b-row class="justify-content-end align-items-center">
            <b-col cols="12" md="3">
              <div class="logo-main-footer">
                <img
                  src="../../assets/images/Bitmap.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
            </b-col>
            <b-col cols="12" md="9">
              <div class="right-footer-content">
                <ul>
                  <li>
                    <img
                      src="../../assets/images/mail.svg"
                      class="img-fluid"
                      alt=""
                    />support@biometric.com
                  </li>
                  <li>
                    <img
                      src="../../assets/images/globe-icon.svg"
                      class="img-fluid"
                      alt=""
                    />English
                    <img
                      src="../../assets/images/arrow-white.svg"
                      alt="Logo"
                      class="img-fluid"
                    />
                  </li>
                  <li>
                    <img
                      src="../../assets/images/help-circle.svg"
                      class="img-fluid"
                      alt=""
                    />Help
                  </li>
                </ul>
              </div>
            </b-col>
          </b-row>
          <b-row>
            <b-col cols="12">
              <hr />
              <div class="footer-bottom text-center">
                <div class="footer-navigation">
                  <ul>
                    <li>Home</li>
                    <li>How it works</li>
                    <li>Knowledge Base</li>
                    <li>Tutorials</li>
                    <li>About</li>
                    <li>FAQs</li>
                    <li>Terms and Conditions</li>
                    <li>Privacy Policy</li>
                    <li>Legal</li>
                  </ul>
                </div>
                <p class="copyright">
                  <span class="copy-text"
                    >Copyright
                    <span class="copy-img">
                      <img
                        src="../../assets/images/copyright-symbol.png"
                        class="img-fluid "
                        alt=""
                      /> </span
                  ></span>

                  <span class="copy-dis"> 2021 GSMA.All right reserved</span>
                </p>
                <div class="scroll-top" v-on:click="scrollTop">
                  <img
                    src="../../assets/images/backtotop-arrow.svg"
                    class="img-fluid "
                    alt=""
                  />
                </div>
              </div>
            </b-col>
          </b-row>
        </b-container>
        <div class="img-footer-biometric">
          <img
            src="../../assets/images/footer-bg-image.svg"
            class="img-fluid"
            alt=""
          />
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Footer",

  methods: {
    scrollTop() {
      window.scrollTo({ left: 0, top: 0, behavior: "smooth" });
    },
  },
};
</script>

<style>
ul {
  list-style: none;
}
.app-downloading-wrapper .downloading-frame {
  background-image: url("../../assets/images/woman-3083376_1920.svg");
  min-height: 386px;
  text-align: center;
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  position: relative;
  display: flex;
  color: #fff;
  justify-content: center;
  align-items: center;
}
.app-downloading-wrapper .downloading-frame ul,
.os-system-wrap {
  display: block;
  padding-left: 0;
  margin: auto;
  text-align: center;
}
.app-downloading-wrapper .downloading-frame ul li,
.os-system-wrap ul li {
  display: inline-block;
  list-style-type: none;
  padding: 20px 0;
  padding-right: 10px;
}
.os-system-wrap ul li img {
  max-width: 100px;
}
.new-case-wrapper .news-frame {
  z-index: 9;

  color: #fff;
  border-radius: 5px;
  position: absolute;
  width: 100%;
  left: 0;
  right: 0;
  padding-top: 26px;
  padding-right: 26px;
  padding-bottom: 26px;
  padding-left: 29px;
  top: calc(100px - 157px);
}
.footer-wrapper .right-footer-content ul {
  padding-left: 0;
  padding-bottom: 0;
  margin-bottom: 0;
}

.bg-1 {
  background: #95236c;
}
*,
::after,
::before {
  box-sizing: border-box;
}
div {
  display: block;
}

.btn-newscase {
  color: #95236c;
  background: #fff;
  padding: 16px 30px;
  line-height: normal;
  border-radius: 5px;
  margin: 20px 10px;
}
.footer-wrapper .right-footer-content ul li img {
  padding-right: 5px;
}
.btn-newscase:hover {
  color: #95236c;
  text-decoration: none;
}
footer ul {
  display: block;
}
footer ul li,
footer ul li a {
  display: inline-block;
  list-style-type: none;
  font-size: 12px;
  line-height: normal;
}
footer p.copyright {
  font-size: 12px;
}
.footer-wrapper {
  min-height: 308px;
  position: relative;
  color: #fff;
  /* height: 308px; */
  justify-content: center;
  align-items: center;
  display: flex;
  padding-top: 65px;
}

/* .footer-wrapper .footer-headline {
  padding-top: 100px;
} */
.footer-wrapper .right-footer-content {
  display: flex;
  justify-content: flex-end;
  align-items: flex-end;
}
.footer-wrapper .right-footer-content ul li {
  list-style: none;
  padding: 20px 10px;
  display: inline-block;
  padding-bottom: 0;
  padding-right: 50px;
  padding-top: 0;
}
.footer-wrapper .right-footer-content ul li:last-child {
  padding-right: 0;
}
.footer-wrapper .footer-bottom ul li {
  padding: 20px 10px;
}
.footer-bottom .text-center {
  text-align: center !important;
}
.footer-bg {
  background: #181818;
}
*,
::after,
::before {
  box-sizing: border-box;
}
hr {
  background: #d8d8d8;
  margin-top: 1rem;
  margin-bottom: 1rem;
  border: 0;
  border-top: 1px solid #3c3c3c;
}
.footer-bottom {
  position: relative;
}
.footer-wrapper .img-footer-biometric {
  position: absolute;
  right: 0;
  bottom: 0;
}
.copyright img {
  margin-left: 5px;
  margin-right: 5px;
}
.scroll-top {
  position: absolute;
  right: 2px;
  top: 20px;
  border-radius: 5px;
  background: #95236c;
  width: 50px;
  height: 50px;
  line-height: 50px;
  z-index: 99;
}
.new-case-wrapper .newscase-headline p {
  padding-bottom: 0;
  margin-bottom: 0;
}
.new-case-wrapper .newscase-headline h2 {
  padding-bottom: 11px;
  margin-bottom: 0;
}
.copy-text {
  position: relative;
  padding-right: 17px;
}
.copy-img {
  content: "";
  width: 12px;
  height: 12px;
  background-image: url("../../assets/images/footer-bg-image.svg");
  background-size: contain;
  background-position: center;
  position: absolute;
  right: 8px;
  top: -6px;
  bottom: 0;
}

.footer-navigation ul {
  padding-left: 0;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
@media only screen and (min-width: 1200px) {
  .footer-wrapper .container {
    max-width: 1171px;
  }
}
@media only screen and (max-width: 993px) {
  .footer-wrapper {
    padding-top: 143px;
  }
  .scroll-top {
    display: none;
  }
  .footer-wrapper .footer-bottom ul li {
    display: list-item;
  }
  .news-head {
    flex-wrap: wrap;
  }
  .news-head .newscase-headline {
    margin-bottom: 30px;
    width: 100%;
    text-align: center;
  }
  .new-case-wrapper .newscase-btn {
    width: 100%;
    text-align: center;
  }
}
@media only screen and (max-width: 767px) {
  .footer-navigation ul {
    display: block;
  }
  .footer-wrapper .footer-bottom ul li {
    padding-bottom: 0;
  }
  .footer-wrapper {
    padding-top: 163px;
  }
  .footer-wrapper .logo-main-footer {
    margin: auto;
    text-align: center;
    margin-bottom: 10px;
  }
  .footer-wrapper .right-footer-content ul {
    margin: auto;
    text-align: center;
  }
  .footer-wrapper .right-footer-content ul li {
    padding-left: 0;
    margin-bottom: 15px;
    padding-right: 0;
  }
  .footer-wrapper .right-footer-content ul li:first-child {
    width: 100%;
  }
  .footer-wrapper .right-footer-content ul li:nth-of-type(2) {
    padding-right: 37px;
  }
  .new-case-wrapper .news-frame {
    text-align: center;
    margin: 0 15px;
    width: auto;
  }

  .new-case-wrapper .news-frame {
    top: calc(100% - 132px);
  }
}
</style>
