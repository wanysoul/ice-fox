<template>
  <div class="home" style="height: 100%">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/> -->
    <div class="container">
    <div class="columns">
      <div class="column col-6">col-6</div>
      <div class="column col-3">col-3</div>
      <div class="column col-2">col-2</div>
      <div class="column col-1">col-1</div>
    </div>
  </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Component({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {

  mounted () {
    this.greet()
  
  }

  greet () {
      // let MongoClient = require('mongodb').MongoClient
      //   , assert = require('assert');
      console.dir(Promise)

      // Connection URL
      // let url = 'mongodb://localhost:27017/mydb';

      // // Use connect method to connect to the server
      // MongoClient.connect(url, function(err, db) {
      //   // assert.equal(null, err);
      //   console.log("Connected successfully to server");

      //   db.close();
      // });
    }
}
</script>
