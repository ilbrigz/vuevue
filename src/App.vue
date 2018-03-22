<template>
  <div id="app">
 <div>
    <v-alert type="success" :value="true">
      This is a success alert.
    </v-alert>

    <v-alert type="info" :value="true">
      This is a info alert.
    </v-alert>

    <v-alert type="warning" :value="true">
      This is a warning alert.
    </v-alert>

    <v-alert type="error" :value="true">
      This is a error alert.
    </v-alert>
  </div>
  </div>
</template>

<script>

export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>
@import "./assets/main"

</style>
