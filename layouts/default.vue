<template>
  <div class="globalContainer">
    <main class="main">
      <nuxt />
    </main>
  </div>
</template>

<style lang="stylus">
html
  font-family mainFont
  font-size 16px
  word-spacing 1px
  -ms-text-size-adjust 100%
  -webkit-text-size-adjust 100%
  -moz-osx-font-smoothing grayscale
  -webkit-font-smoothing antialiased
  box-sizing border-box
  color black
  background whiteSoft

.main
  min-height 100vh
  display flex
  flex-flow column nowrap
  justify-content space-between
  overflow-x hidden
</style>
