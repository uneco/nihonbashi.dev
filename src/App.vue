<template lang="pug">
#app
  h1 AKIHABARA.DEV
  p
    a(:href='tweet', target='_blank')
      .image
        img(src='./assets/cat.gif')
      p なに？
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component({})
export default class App extends Vue {
  public tweet = 'https://twitter.com/unecochan/status/1101164940163833857'
}
</script>

<style lang="sass">
#app
  font-family: 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50
  margin-top: 60px

  a
    color: #9aa83a
</style>
