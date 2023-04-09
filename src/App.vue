<template>
  <router-link to="/login">登录</router-link>
  <router-link to="/main">主页</router-link>
  <p>{{ $store.state.name }}</p>
  <div class="rounded-3xl bg-dark-300" style="width: 200px;height: 200px;"></div>
  <router-view></router-view>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',
  components: {}
})
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
// .rounded-3xl {
//   border-radius: 1.5rem;
// }
</style>
