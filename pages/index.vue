<template>
  <v-app>
    <slideshow></slideshow>
    <v-container>
    <v-card>
        <v-layout wrap align-content-space-around>
        <v-flex><card></card></v-flex>
        <v-flex><card></card></v-flex>
        <v-flex><card></card></v-flex>
        <v-flex><card></card></v-flex>
        <v-flex><card></card></v-flex>
        <v-flex><card></card></v-flex>
        </v-layout>
    </v-card>
    </v-container>
  </v-app>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  layout: 'home',
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
