<template>
  <div id="app">
    <div id="nav" class="container">
      <div class="row">
        <div class="col">
          <router-link to="/">Home</router-link> |
          <router-link to="/about">About</router-link>
        </div>
      </div>
    </div>
    <div class="container">
      <router-view/>
    </div>
  </div>
</template>

<style lang="scss">
  @import '@/components/scss/index.scss';
</style>
