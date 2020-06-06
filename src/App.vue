import { default } from './components/HelloWorld.vue';
<template>
  <main>
    <br-header/>
    <br-assets-table/>
  </main>
</template>

<script>
import  BrHeader  from "@/components/BrHeader";
import  BrAssetsTable  from "@/components/BrAssetsTable";

  export default {
    name: "app",
    components: {
      BrHeader,
      BrAssetsTable
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
