<template>
  <div class="container">
    <!-- <app-header></app-header> -->
    <router-view keep-alive></router-view>
    <app-footer></app-footer>
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.min.css'
import AppHeader from './components/header.vue'
import AppFooter from './components/footer.vue'

export default {
  components: {
    'app-header': AppHeader,
    'app-footer': AppFooter
  }
}
</script>

<style lang="less">
body {
  background-color: #f4f4f4 !important;
  font-family: "Microsoft Yahei" !important;
}
#app {
  max-width: 740px;
  margin: 100px auto;
  background-color: #fff;
  box-sizing: border-box;
  padding: 55px;
  border-radius: 6px;
  position: relative;
  padding-bottom: 30px;
}
</style>
