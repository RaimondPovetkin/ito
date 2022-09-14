<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <v-btn
      @click="foo"
    >
      click
    </v-btn>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  methods:{
    foo(){
      this.$router.push('about')
    }
  }
}
</script>
