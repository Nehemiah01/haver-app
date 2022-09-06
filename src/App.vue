<template>

  <!-- <nav>
    <router-link to="/">Home</router-link> |
  </nav>
  <router-view/> -->

  <!-- <Nav /> -->
  <!-- <Search /> -->
  <!-- <Groups/> -->
  <Recents/>
  
</template>

<script>
import Nav from '@/components/Nav'
import Search from './components/Search.vue';
import Groups from './components/Groups.vue';
import Recents from './components/Recents.vue';

export default {
  components: {
    Nav,
    Search,
    Groups,
    Recents
  }
}

</script>

<style lang="scss">
  
* {
  font-family: "Poppins";
}

body {
  background-color: #eee;
}

nav {
  // padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}


</style>
