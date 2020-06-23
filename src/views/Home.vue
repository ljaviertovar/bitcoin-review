<template>
  <div>
    <br-assets-table v-bind:assets="assets"/>
  </div>
</template>

<script>
import api from "@/api";
import BrAssetsTable from "@/components/BrAssetsTable";

export default {
  name: "home",
  components: {
    BrAssetsTable,
  },
  data() {
    return {
      assets: [],
    };
  },
  created() {
    api.getAssets().then((assets) => (this.assets = assets));
  },
};
</script>
