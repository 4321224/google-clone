<template>
  <div class="headerRight">
    <router-link class="menu-item _menu _link" to="/"> Gmail</router-link>
    <router-link class="menu-item _menu _link" to="/"> Images</router-link>
    <div class="menu-item _menu">
      <v-icon color="blue-grey darken-2"> mdi-apps</v-icon>
    </div>
    <div class="menu-item">
      <v-icon color="blue-grey darken-2"> mdi-account-circle</v-icon>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Appbar",
  };
</script>

<style scoped>
  .headerRight {
    display: flex;
    font-size: 13px;
    color: rgba(0, 0, 0, 0.87);
    position: relative;
    right: 0;
    top: 15px;
    z-index: 2;
  }
  .menu-item {
    padding-top: 7px;
    padding: 5px;
  }
  .menu-item._menu {
    padding-top: 13px;
  }
  .menu-item._menu._link {
    padding-top: 16px;
  }

  a:visited {
    color: rgba(0, 0, 0, 0.87);
  }
  a {
    color: rgba(0, 0, 0, 0.87);
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
</style>
