<template>
  <header class="site-header header-one ">
    <nav :class="`navbar navbar-expand-lg navbar-light header-navigation stricky ${sticky ? 'stricked-menu stricky-fixed' : ''}`">
      <div class="container clearfix">
          <!-- Brand and toggle get grouped for better mobile display -->
        <div class="logo-box clearfix">
          <a class="navbar-brand" href="/">
            <img src="/images/logo-light.png" class="main-logo" width=180 alt="Awesome Image" />
          </a>
          <!--<button class="menu-toggler" data-target=".main-navigation" style = "color:#74BAD8">-->
            <button class="menu-toggler" data-target=".main-navigation">
            <span @click="mobileToggle = !mobileToggle" class="fa fa-bars"></span>
          </button>
        </div><!-- /.logo-box -->
        <!-- Collect the nav links, forms, and other content for toggling -->
        <div :class="`main-navigation ${mobileToggle ? 'showen' : ''}`" :style="`display: ${mobileToggle ? 'block' : 'none'}`">
          <ul class=" navigation-box one-page-scroll-menu ">
            <li class="current scrollToLink">
              <a href="#home">Home</a>
            </li>
            <li class="scrollToLink">
              <a href="#services">About Us</a>
            </li>
            <li class="scrollToLink">
              <a href="#CallToActionThree">our Mission</a>              
            </li>
            
            <li class="scrollToLink">
              <a href="#pricing">Our Technology</a>              
            </li>
            <li class="scrollToLink">
              <a href="#testimonials">Applications</a>             
            </li>
            <li class="scrollToLink">
              <a href="#contact">Contact</a>
            </li>
          </ul>
        </div><!-- /.navbar-collapse -->        
      </div>
      <!-- /.container -->
    </nav>


  </header>
</template>

<script>
  export default {
    name: "Nav",
    data(){
      return {
        sticky: false,
        mobileToggle: false
      }
    },
    mounted() {
      window.addEventListener('scroll', this.handleScroll);
    },
    methods: {

      handleScroll() {
        if (window.scrollY > 70) {
          this.sticky = true
        } else if (window.scrollY < 70) {
          this.sticky = false
        }
      },
    }
  }
</script>

<style scoped>

</style>
