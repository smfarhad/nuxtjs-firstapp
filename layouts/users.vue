<template>
  <div>
    <Header />
    <div class="container page">
      <nuxt />
    </div>
  </div>
</template>
<script>
import Header from "~/components/Header.vue";
export default {
  components: {
    Header
  }
};
</script>
 <style scoped>
.page {
  margin-top: 25px;
}
</style>