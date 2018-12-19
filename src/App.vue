<template lang="pug">
  div#app
    div#nav
      router-link(to="/") Home
      router-link(to="/about") About
    transition(name="slide-fade" )
      router-view.view
</template>

<style lang="scss">
  @import '@/styles/main.scss';
</style>
