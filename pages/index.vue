<template>
  <div class="home-page">
    <div class="container">
      <div class="page-content">
        <div class="page-header">
          <img class="geode-logo" src="~assets/geode-logo.png" alt="geode logo">
        </div>
        <div class="page-slogans">
          <div class="slogan"><strong>share</strong> cool things, </div>
          <div class="slogan"><strong>discover</strong> something new, </div>
          <div class="slogan"><strong>&amp; reward</strong> creators with crypto</div>
        </div>
        <div class="input-group">
          <!--<input type="text" placeholder="your email">-->
          <!--<button>HODL🚀</button>-->
          <form action="https://network.us17.list-manage.com/subscribe/post?u=02a6dbdcae7af4655c9b2ac03&amp;id=945f88b53f" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
              <div id="mc_embed_signup_scroll">

          	<input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="your email" required>
              <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
              <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_02a6dbdcae7af4655c9b2ac03_945f88b53f" tabindex="-1" value=""></div>
              <button><input type="submit" value="HODL🚀" name="hodl" id="mc-embedded-subscribe" class="button"></button>
              </div>
          </form>

        </div>
        <div class="gallery-img-mobile">
          <img src="~assets/geode-imgs-mobile.png" alt="geode logo">
        </div>
        <div class="app-info-wrapper">
          <div class="app-info">
            <p class="paragraph"><span class="linebreak">We're inviting 10,000 creators to join Steem!</span><span class="linebreak">Nominate the most talented people you know <a href="https://byzantine.typeform.com/to/ul7Woi"><span class="highlight">for a free account</span></a></span></p>
            <div class="line"></div>
            <p class="paragraph">Let's get to 1 million Steem Power, together: <a href="https://busy.org/@geode.cool"><span class="highlight">Learn how to delegate</span></a></p>
          </div>
        </div>
        <div class="page-footer">
          <ul class="media-list">
            <li><a href="https://busy.org/@geode.cool" target="_blank"><img src="~/assets/busy-icon.png" alt="busy icon"></a></li>
            <li><a href="https://d.tube/#!/c/geode.cool" target="_blank"><img src="~/assets/dtube-icon.png" alt="dtube icon"></a></li>
            <li><a href="https://www.dlive.io/#/user/geode.cool" target="_blank"><img src="~/assets/dlive-icon.png" alt="dlive icon"></a></li>
            <li><a href="https://www.facebook.com/geode.cool" target="_blank"><img src="~/assets/facebook-icon.png" alt="facebook icon"></a></li>
          </ul>
          <div class="copyright">
            <div class="byzantine-thing"><a href="http://www.byzantine.network/"><span class="highlight">A Byzantine thing</span></a> | Byzantine Inc. 2018</div>
            <div class="creativecommons"><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><span class="highlight">Creative Commons Attribution 4.0 International License</span></a>.</div>
            <div class="credits"><br />Featured images credit due to the always awesome <a rel="license" href="https://www.behance.net/beeple"><span class="highlight">Mike Winkelmann</span></a>.</div>
          </div>
        </div>
      </div>
      <div class="gallery-image">
        <img src="~assets/geode-img-laptop.png" alt="gallery images">
      </div>
    </div>
  </div>
</template>

<script>
// import AppLogo from '~/components/AppLogo.vue'

// export default {
//   components: {
//     AppLogo
//   }
// }
</script>

<style scoped>
.container {
  display: flex;
}

.page-content {
  flex: 1 1 auto;
  padding: 24px;
}
.geode-logo {
  height: 50px;
}
.page-slogans {
  padding: 24px 0;
  font-size: 3.4vw;
}

.input-group {
  display: flex;
  margin: 20px 0 50px;
  width: 100%;
  max-width: 400px;
}
.input-group input {
  flex: 1 1 auto;
  vertical-align: top;
  margin-right: -1px;
  padding: 16px;
  margin-top: 10px;
  height: 40px;
  width: 280px;
  border: 1px solid #616161;
}
.input-group button {
  flex: 0 0 auto;
  vertical-align: top;
  height: 40px;
  width: 120px;
  margin-top: 10px;
  background: linear-gradient(45deg, #b1fdd8, #96f3ff, #c7b0fd, #f3cbe4);
  border: 1px solid #616161;
  font-size: 1.1em;
  color: #5a5a5a;
  letter-spacing: 3px;
}
.input-group button input {
  flex: 0 0 auto;
  vertical-align: top;
  height: 40px;
  width: 120px;
  padding: 0;
  margin-left: -5px;
  margin-top: 0;
  background: transparent;
  border: 0;
  font-size: 1.1em;
  font-family: "Avenir Next", Arial, Helvetica, sans-serif;
  color: #5a5a5a;
  letter-spacing: 3px;
}

.gallery-img-mobile {
  display: none;
  margin-left: -24px;
  margin-right: -24px;
}
.gallery-img-mobile img {
  width: 100%;
}

.app-info-wrapper {
  position: relative;
  z-index: 1;
  margin-left: -24px;
  margin-top: 18px;
  padding: 24px;
}
.app-info-wrapper:before {
  content: '';
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: linear-gradient(45deg, #b1fdd8, #96f3ff, #c7b0fd, #f3cbe4);
  opacity: .4;
}
.app-info {
  position: relative;
}
.paragraph {
  padding: 16px 0;
  line-height: 1.4em;
}
.paragraph .linebreak {
  display: block;
}
.paragraph a{
  text-decoration: none;
}
.highlight {
  color: #f466ac;
}
.byzantine-thing {
  padding-top: 30px;
}
.byzantine-thing a {
  text-decoration: none;
}
.creativecommons {

}
.creativecommons a {
  text-decoration: none;
}
.credits {

}
.credits a {
  text-decoration: none;
}
.app-info .line {
  width: 100%;
  max-width: 300px;
  border: 1px solid #ddd;
}

.media-list {
  margin-top: 24px;
  margin-bottom: 10px;
  padding: 0;
  list-style: none;
}
.media-list li {
  display: inline-block;
  vertical-align: top;
  margin-right: 16px;
  height: 40px;
}
.media-list img {
  height: 100%;
}
.copyright {
  font-size: .7em;
  color: #bdbdbd;
}

.gallery-image {
  flex: 0 0 auto;
  height: 100vh;
  overflow: hidden;
}
.gallery-image img {
  height: 100%;
}

@media (max-width: 940px) {
  .page-slogans {
    font-size: 6vw;
  }
  .gallery-img-mobile {
    display: block;
  }
  .app-info-wrapper {
    margin-right: -24px;
  }
  .gallery-image {
    display: none;
  }
}
@media (max-width: 786px) {
  .page-slogans {
    font-size: 7vw;
  }
  .slogan {
    display: inline;
  }
}
@media (max-width: 683px) {
  .page-slogans {
    font-size: 8vw;
  }
}
</style>
