<template>
  <div class="headerRight">
    <router-link class="menu-item_menu_link" to="/"> Gmail</router-link>
    <router-link class="menu-item_menu_link" to="/"> Images</router-link>
    <div class="menu-item_menu">
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

<style></style>
