<template>
  <div class="navbar">
    <nav class="nav-extended indigo bg-darken-2">
      <div class="nav-content">
        <router-link to="/">
          <span class="nav-title">Smoothies</span>
        </router-link>
        <a class="btn-floating btn-large halfway-fab pink">
          <router-link to="/add">
            <i class="material-icons">add</i>
          </router-link>
        </a>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {};
  }
};
</script>

<style>
.navbar nav {
  padding: 0 20px;
}
</style>