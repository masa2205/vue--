<template>
  <v-app>
    <v-app-bar color="info" dark app clipped-left>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-toolbar-title class="headline text-uppercase">
        <span>マイアドレス帳</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
    </v-app-bar>
    <SideNav/>
    <FooterNav/>

  </v-app>
</template>

<script>
import SideNav from './components/SideNav'
import FooterNav from './components/FooterNav'
export default {
  name: 'App',
  components: {
    SideNav,
    FooterNav
  },
  data () {
    return {
      //
    }
  }
}
</script>
