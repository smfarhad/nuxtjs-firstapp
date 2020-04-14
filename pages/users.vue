<template>
  <div>
    <form v-on:submit.prevent>
      <input v-model="userId" type="text" value />
      <button type="submit" class="btn btn-primary" @click="onLoadUser()">Load User</button>
    </form>
    <nuxt-child />
  </div>
</template>
<script>
export default {
  data() {
    return {
      userId: ""
    };
  },
  components: {},
  methods: {
    onLoadUser() {
      this.$router.push("/users/" + this.userId);
    }
  },
  layout: "users"
};
</script>