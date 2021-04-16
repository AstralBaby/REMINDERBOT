/* eslint-disable */
<template>
  <div id="app">
    <button>google</button>
    {{name}}
    <input type="text" v-model="name">
    <MyButton :text='name'>
    </MyButton>
    <MyButton text='owo'>
    </MyButton>
  </div>
</template>

<script>
import MyButton from './components/MyButton.vue';

export default {
  name: 'App',
  components: {
    MyButton,
  },
  data: function(){
    return {
      name: ''
    }
  }
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