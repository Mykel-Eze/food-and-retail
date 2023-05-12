<template>
  <div>
    <nav class="main-nav">
      <div class="container">
        <div class="nav-wrapper">
          <router-link to="/" class="brand-logo" @click="scrollToTop()">
            <img src="../assets/images/jfr-white.svg" alt="Japtini" class="logo logo-default">
            <img src="../assets/images/jfr-colored.svg" alt="Japtini" class="logo logo-scrolled">
          </router-link>

          <ul id="nav-mobile" class="right">
            <li class="contact-us-li">
              <a href="mailto:contact@japtinifoods.com">
                <button class="nav-pry-btn btn">Contact Us</button>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>

export default {
  name: 'NavbarComp',
  mounted () {},
  methods: {
    scrollToTop () {
      window.scrollTo(0, 0)
    }
  }
}
</script>

<style scoped src="..\assets\css\navbar.css"></style>
