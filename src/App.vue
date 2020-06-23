import { default } from './components/HelloWorld.vue';
<template>
  <main>
    <br-header/>
    <router-view class="container px-5 sm:px-20 py-10 flex justify-centery"/>
  </main>
</template>

<script>
import  BrHeader  from "@/components/BrHeader";

  export default {
    name: 'app',
    components: {
      BrHeader,
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
  margin-top: 60px;
}
</style>
