<template>

  <section id="content">
    <Header />
    <router-view></router-view>
    <Footer />
  </section>

</template>

<script>
import Header from './components/Header'
import Footer from './components/Footer'



export default {
  name: 'App',
  components:{
    Header,
    Footer
  }
}

</script>



<style>

*{
  margin: 0;
	padding: 0;
	box-sizing: border-box;
	outline: none;
	list-style: none;
	text-decoration: none;
	scroll-behavior: smooth;
  font-family: 'Ubuntu', sans-serif;
}

</style>
