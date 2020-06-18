<template>
  <div class="app">
    <router-view class="app__content"/>
  </div>
</template>
<script>
  export default {
    name: 'App'
  }
</script>

<style lang="scss">
*,
*::after,
*::before {
  box-sizing: inherit;
}

html {
  box-sizing: border-box;
}

body {
  font-family: $main-font;
}
</style>
