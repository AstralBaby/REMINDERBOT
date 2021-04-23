/* eslint-disable */
<template>
    <div id="app">
      <!-- <button>google</button>
     {{name}}
     <input type="text" v-model="name"> -->
      <Sidebar>
      </Sidebar>
      <Container>
      </Container>
    </div>
</template>

<script>
import Sidebar from './components/layouts/sidebar.vue'
import Container from './components/layouts/container.vue'
export default {
  name: 'App',
  components: {
    Sidebar, Container,
  },
  data: function(){
    return {
      name: ''
    }
  }
};
</script>

<style>
html, body, #app{
  margin: 0;
  padding: 0;
  border: 0;
  width: 100%;
  height: 100%;
}
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
  display:flex;
  flex-grow: 1;
}
</style>