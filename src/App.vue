<template>
  <navbar />
  <router-view />
</template>

<script>
import Navbar from "@/views/components/navbar/Navbar.vue";

export default {
  components: { Navbar },
};
</script>
<style lang="sass">
@import "../node_modules/bulma/bulma.sass"
</style>
