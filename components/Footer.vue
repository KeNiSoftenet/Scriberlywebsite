<template>
  <div>
  <footer class="site-footer">
    <div class="site-footer__upper">
      <div class="container">
        <div class="site-footer__5-col-wrap">
          <div class="footer-widget footer-widget__about">
            <a href="/" class="footer-widget__logo"><img width="150" src="/images/logo-light-1.png" alt="Awesome Image" /></a>
          </div><!-- /.footer-widget -->
          <div class="footer-widget">
            <h3 class="footer-widget__title">Explore</h3><!-- /.footer-widget__title -->
            <ul class="footer-widget__links">
              <li class="footer-widget__links-item">
                <a href="#services" class="footer-widget__links-link">About Us</a>
              </li><!-- /.footer-widget__links-item -->
              <li class="footer-widget__links-item">
                <a href="#CallToActionThree" class="footer-widget__links-link">Our Mission</a>
              </li><!-- /.footer-widget__links-item -->
              <li class="footer-widget__links-item">
                <a href="#pricing" class="footer-widget__links-link">Our Technology</a>
              </li><!-- /.footer-widget__links-item -->
              <li class="footer-widget__links-item">
                <a href="#testimonials" class="footer-widget__links-link">Applications</a>
              </li><!-- /.footer-widget__links-item -->              
            </ul><!-- /.footer-widget__links -->
          </div><!-- /.footer-widget -->
          <div class="footer-widget footer-widget__subscribe">
            <h3 class="footer-widget__title">Subscribe</h3><!-- /.footer-widget__title -->
            <form action="#" class="footer-widget__subscribe-form">
              <input type="text" name="email" placeholder="Email address">
              <button type="submit"><i class="fa fa-location-arrow"></i></button>
            </form><!-- /.footer-widget__subscribe-form -->
          </div><!-- /.footer-widget -->
        </div><!-- /.site-footer__5-col-wrap -->
      </div><!-- /.container -->
    </div><!-- /.site-footer__upper -->
    <div class="site-footer__lower">
      <div class="container">
        <div class="inner-container">
          <p class="site-footer__copytext">© copyright 2021 by <a href="#">KeNiTechnologiesLLP</a></p><!-- /.site-footer__copytext -->
          <div class="site-footer__social">
            <a href="#"><i class="fa fa-facebook"></i></a>
            <a href="#"><i class="fa fa-twitter"></i></a>
            <a href="#"><i class="fa fa-linkedin"></i></a>
            
          </div><!-- /.site-footer__social -->
        </div><!-- /.inner-container -->
      </div><!-- /.container -->
    </div><!-- /.site-footer__lower -->
  </footer>

    <a @click="scrollTop" class="scroll-to-target scroll-to-top" :style="`display: ${scrollBtn ? 'inline' : 'none'}`" href="#"><i class="fa fa-angle-up"></i></a>
  </div>
</template>

<script>
  export default {
    name: "Footer",
    data(){
      return {
        scrollBtn: false
      }
    },
    mounted() {
      window.addEventListener('scroll', this.handleScroll);
    },

    methods: {

      handleScroll () {

        if (window.scrollY > 70) {
          this.scrollBtn = true
        }
        else if (window.scrollY < 70) {
          this.scrollBtn = false
        }
      },

      scrollTop () {
        window.scrollTo(0, 0);
      }


    }
  }
</script>

<style scoped>

</style>
