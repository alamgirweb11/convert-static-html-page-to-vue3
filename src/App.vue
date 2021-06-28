<template>
    <div id="app">
      <Header></Header>
       <Banner></Banner>
       <AboutUs></AboutUs>
       <Service></Service>
       <Portfolio></Portfolio>
      <Footer></Footer>
      
      
    
    </div>
</template>

<script>
import Header from "./components/Header.vue"
import Banner from "./components/Banner.vue"
import AboutUs from "./components/AboutUs.vue"
import Service from "./components/Service.vue"
import Portfolio from "./components/Portfolio.vue"
import Footer from "./components/Footer.vue"


export default {
  name: "App",
  components: {
     Header,
     Banner,
     Footer,
     AboutUs,
     Service,
     Portfolio,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
