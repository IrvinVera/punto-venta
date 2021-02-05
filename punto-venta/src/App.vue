<template>
  <v-app>
    <v-main class="login">
      <Login />
    </v-main>
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';

import Login from './views/Login';

export default {
  name: 'App',

  components: {
    Login,
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
.login{
  height: 100%;
}
</style>
