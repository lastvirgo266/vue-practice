<template>
  <v-app id = "app">
    <menus></menus>
    <router-view></router-view>
  </v-app>
</template>

<script>
import Menus from './components/Menus.vue'
export default {
  components: {Menus},
}
</script>