<template>

  <body class="hold-transition sidebar-mini layout-fixed layout-navbar-fixed layout-footer-fixed">
    <div class="wrapper"> 
          <!-- <router-link to="/Home">Home</router-link>
          <router-link to="/Navbar">Navbar</router-link>
          <router-link to="/Content">Content</router-link>
          <router-link to="/Sidebar">Sidebar</router-link>
          <router-link to="/Footer">Footer</router-link> -->
          <!-- <Navbar/> -->
                  <router-view></router-view>
          <!-- <Sidebar/> -->
          <!-- <Content/> -->
          <!-- <Footer/> -->
    </div>
  </body>

</template>

<script>

// import Navbar from './components/Navbar.vue'
// import Sidebar from './components/Sidebar.vue'
// // import Content from './components/Content.vue'
// import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    // Navbar,
    // Sidebar,
    // // Content,
    // Footer
  },
  
}


</script>
<style  scoped>
@import "./assets/Css/style.css"; 
/* @import "./assets/admin-lte/css/adminlte.scss"; */
.slide-enter-active , .slide-enter-active{
  transition: opacity 1 , transform 1;
}
.slide-leave , .slide-leave-to{
  opacity: 0;
  transform: translateX(-30%);

}
</style>
