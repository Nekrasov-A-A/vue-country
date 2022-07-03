<template>
  <div id="app">
    <nav>
      <router-link to="/" class="test">Home</router-link>
      <div>Test</div>
    </nav>
    <router-view />
  </div>
</template>

<style lang="sass" scoped>
.test
  color: $bg-dark
</style>
