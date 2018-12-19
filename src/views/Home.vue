<template lang="pug">
  div.home
    .container.has-text-centered
      .column.is-6.is-offset-3
        h1.title
          | Home
        h2.subtitle
        | Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        | tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        | quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        | consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        | cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        | proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src

@Component({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>
