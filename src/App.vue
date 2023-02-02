<script>
import HelloWorldMio from './components/HelloWorldMio.vue'
import HelloWorldMioImg from './components/HelloWorldMioImg.vue';
export default {
    name :"App",
  data() {
    return {
     msg:"Ciao Vite",
     count:0
    };
  },
  components:{
    HelloWorldMio,
    HelloWorldMioImg
  },
}
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
    <h1>Ciao da Leo</h1>
  </div>
  <HelloWorldMio/>  
  <HelloWorldMioImg/>
</template>
 
<style>
h1 { 
  color:green;
}
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
