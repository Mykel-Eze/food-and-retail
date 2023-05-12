<template>
  <footer>
    <div class="row">
      <div class="container">
        <div class="footer-contents-wrapper">
          <div class="footer-content-block footer-logo-block">
            <router-link to="/" @click="scrollToTop()">
              <img src="../assets/images/jfr-colored.png" alt="Japtini Food and Retial" class="footer-logo">
            </router-link>
          </div>
          <div class="footer-content-block">
            <div class="footer-sec-content">
              <ul>
                <li>
                  <a href="tel:+234700000000" class="footer-sec-link">+234 700 000 000</a>
                </li>
                <li>
                  <a href="mailto:contact@japtinifoods.com" class="footer-sec-link">contact@japtinifoods.com</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="footer-content-block">
            <h4 class="footer-sec-title">
              Follow Us
            </h4>
            <div class="footer-social-wrapper">
              <a href="http://facebook.com" target="_blank" rel="noopener noreferrer">
                <img src="../assets/images/facebook.svg" alt="facebook" class="social-icons default-icon">
                <img src="../assets/images/facebook-hover.svg" alt="facebook" class="social-icons hover-icon">
              </a>
              <a href="https://twitter.com" target="_blank" rel="noopener noreferrer">
                <img src="../assets/images/twitter.svg" alt="twitter" class="social-icons default-icon">
                <img src="../assets/images/twitter-hover.svg" alt="twitter" class="social-icons hover-icon">
              </a>
              <a href="https://instagram.com" target="_blank" rel="noopener noreferrer">
                <img src="../assets/images/instagram.svg" alt="instagram" class="social-icons default-icon">
                <img src="../assets/images/instagram-hover.svg" alt="instagram" class="social-icons hover-icon">
              </a>
              <a href="https://linkedin.com" target="_blank" rel="noopener noreferrer">
                <img src="../assets/images/linkedin.svg" alt="linkedin" class="social-icons default-icon">
                <img src="../assets/images/linkedin-hover.svg" alt="linkedin" class="social-icons hover-icon">
              </a>
            </div>
          </div>
        </div>

        <div class="footer-credit-wrapper">
          <div class="footer-sub-wrapperv">
            <div>©2023 Japtini Food and Retails. All Rights Reserved.</div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterSection',
  methods: {
    scrollToTop () {
      window.scrollTo(0, 0)
    }
  }
}
</script>

<style scoped src="..\assets\css\footer.css"></style>
