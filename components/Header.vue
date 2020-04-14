<template>
  <header class="sticky-top">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        <nuxt-link class="navbar-brand" to="/">Logo</nuxt-link>
        <ul class="navbar-nav mr-auto float-right">
          <li class="nav-item active">
            <nuxt-link class="nav-link" to="/">
              Home
              <span class="sr-only">(current)</span>
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/users">User</nuxt-link>
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>
<script>
export default {};
</script>
<style scoped>
</style>