<template>
  <div id="app">
    <!-- <img src="./assets/logo.png">
    <router-view/> -->

    <md-card md-with-hover>
      <md-ripple>
        <md-card-header>
          <div class="md-title">Card with hover effect</div>
          <div class="md-subhead">It also have a ripple</div>
        </md-card-header>

        <md-card-content>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio itaque ea, nostrum odio. Dolores, sed accusantium quasi non.
        </md-card-content>

        <md-card-actions>
          <md-button @click="test01">Test01</md-button>
          <md-button @click="test02">Test02</md-button>
        </md-card-actions>
      </md-ripple>
    </md-card>

  </div>
</template>

<script>
export default {
  name: 'App',
  methods: {
    test00: function() {
      console.log("Test00");
    },
    test01: function() {
      console.log("Test01");
    },
    test02: function() {
      console.log("Test02");
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
