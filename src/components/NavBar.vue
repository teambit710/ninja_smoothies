<template>
  <div class="navbar">
    <nav class="nav-extended indigo darken-2">
      <div class="nav-content">
        <router-link to>
          <span class="nav-title">Ninja Smoothies</span>
          <a href class="btn-floating btn-large halfway-fab pink">
            <router-link to>
              <i class="material-icons">add</i>
            </router-link>
          </a>
        </router-link>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {};
  }
};
</script>