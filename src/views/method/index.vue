<template>
  <div class="container">
  <div class="container-left col-lg-3">111111111111111111111111111</div>
  <div class="container-right">right</div>
  </div>
</template>
<script>
import Vue from 'vue'
import BootstrapVue from 'bootstrap-vue'
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
Vue.use(BootstrapVue)
</script>
<style scoped>
.container-left div {
  width: 280px;
  height: 500px;
  background-color: antiquewhite;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 8px;
}
</style>
