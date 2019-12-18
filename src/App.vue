<template>
  <div id="app">
    <login-one/>
    <login-two/>
  </div>
</template>

<script>

import LoginOne from './components/LoginOne.vue'
import LoginTwo from './components/LoginTwo.vue'

export default {
  name: 'app',
  components: {
    LoginOne,
    LoginTwo
  }
}
</script>