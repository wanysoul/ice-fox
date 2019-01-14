<template>
  <div id="app" class="main">
    <!-- <div style="bac"></div> -->
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <div class="" style="height: 100%">
      <!-- <div class="docs-sidebar off-canvas-sidebar"></div> -->
      
      <div class="columns col-gapless" style="height: 100%">
        <div class="column col-2" >
          <div class="bg-primary docs-block" style="height: 100%"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">COL-6</font></font></div>
        </div>
        <div class="column col-10 bg-gray">
          <router-view/>
        </div>
      </div>
    </div>
    
  </div>
</template>

<style lang="scss">
@import "node_modules/spectre.css/src/spectre";
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.main {
  position: absolute;
    width: 100%;
    height: 100%;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
