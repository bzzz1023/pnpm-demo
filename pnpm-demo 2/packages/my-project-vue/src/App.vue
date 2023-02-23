<template>
  <div>
    <div>111</div>
    <CoolButton />
  </div>
</template>

<script>
import api from '@cool/api'
import { CoolButton } from '@cool/vue-components'
export default {
  name: 'App',
  components: {
    CoolButton
  },
  setup() {
    api()
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
