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
          <input type="text" placeholder="your email">
          <button>HODL🚀</button>
        </div>
        <div class="gallery-img-mobile">
          <img src="~assets/geode-imgs-mobile.png" alt="geode logo">
        </div>
        <div class="app-info-wrapper">
          <div class="app-info">
            <p class="paragraph"><span class="linebreak">We're inviting 10,000 creators to join Steem!</span><span class="linebreak">Nominate the most talented people you know <span class="highlight">for a free account</span></span></p>
            <div class="line"></div>
            <p class="paragraph">1 million Steem Power? <span class="highlight">Learn how to delegate</span></p>
          </div>
        </div>
        <div class="page-footer">
          <ul class="media-list">
            <li><a href="https://busy.org/@geode.cool"><img src="~/assets/busy-icon.png" alt="busy icon"></a></li>
            <li><a href="https://d.tube/#!/c/geode.cool"><img src="~/assets/dtube-icon.png" alt="dtube icon"></a></li>
            <li><a href="https://www.dlive.io/#/user/geode.cool"><img src="~/assets/dlive-icon.png" alt="dlive icon"></a></li>
            <li><a href="https://www.facebook.com/geode.cool"><img src="~/assets/facebook-icon.png" alt="facebook icon"></a></li>
          </ul>
          <div class="copyright">A Byzantine thing | cc Byzantine Inc. 2018</div>
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
  height: 40px;
  border: 1px solid #616161;
}
.input-group button {
  flex: 0 0 auto;
  vertical-align: top;
  height: 40px;
  width: 120px;
  background: linear-gradient(45deg, #b1fdd8, #96f3ff, #c7b0fd, #f3cbe4);
  border: 1px solid #616161;
  font-size: 1.1em;
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
.highlight {
  color: #f466ac;
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
