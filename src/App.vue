<template>
  <div id="app">
    <Layout>
      <NavBar slot="left" />
      <div slot="right">
        <input-form></input-form>
      </div> 
    </Layout>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
  import NavBar from './components/NavBar'
  import Layout from '@/components/Layout'
  import InputForm from '@/components/InputForm'
  export default {
    name: 'App',
    components: {
      // HelloWorld
      NavBar,
      Layout,
      InputForm
    }
  }
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    /* margin-top: 60px; */
  }
  NavBar {
    float: left;
  }
</style>
