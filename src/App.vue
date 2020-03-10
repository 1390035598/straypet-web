<template>
  <div id="app">
    <nav-bar>
      <nav-bar-logo></nav-bar-logo>
    </nav-bar>
    <router-view/>
  </div>
</template>

<script>
import NavBar from 'components/common/NavBar'
import NavBarLogo from 'components/common/NavBarLogo'

export default {
  name: 'app',
  components: {
    NavBarLogo,
    NavBar
  }
}
</script>

<style>
@import "assets/css/base.css";
</style>
