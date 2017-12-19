<template>
  <footer class="">
    VuestarGram정보 지원 블로그 홍보센터.....
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App!!!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import "~styles/variables.scss";

footer{
  width: $content_width;
  margin:0 auto;
}
</style>
