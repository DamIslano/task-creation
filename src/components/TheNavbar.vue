<template>
  <nav class="navbar">
    <router-link to="/">
      <h3>
        Task Manager
      </h3>
    </router-link>

    <ul class="navbar-menu">
      <li>
        <router-link to="/">All tasks</router-link>
      </li>
      <li>
        <router-link to="/new">Create</router-link>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {

}
</script>

<style scoped>

</style>