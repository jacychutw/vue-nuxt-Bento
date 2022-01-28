<template>
  <v-app dark>
    <v-app-bar
      app
      class="d-flex justify-center"
    >
      <v-app-bar-nav-icon />
      <v-toolbar-title v-text="title" style="width:200px;"/>
      <v-app-bar-nav-icon />
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <!-- <v-footer
      :absolute="!fixed"
      app
      class="d-flex justify-center"
    >
      <span>&copy; {{ new Date().getFullYear() }} All Rights Reserved</span>
    </v-footer> -->
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data () {
    return {
      fixed: false,
      title: 'Green Light Bento'
    }
  }
}
</script>
