<template>
  <nav>
    <div class="nav--content">
        <div class="nav--content--logo">
          <span>V</span>uestar<span>G</span>ram
        </div>
        <div class="nav--content--search">
          <input type="text" />
        </div>
        <div class="nav--content--menu">
          <input type="button" value="Login"/>
          <input type="button" value="Sign Up"/>
        </div>
    </div>
  </nav>
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
$nav-height: 70px;

nav{
  min-height: $nav-height;
  line-height: $nav-height;
  background-color:white;
  border-bottom:1px solid rgba(0,0,0,.0975);
}

.nav--content{
  width: $content_width;
  margin:0 auto;

  display:flex;
  justify-content: space-between;

  &--logo {
    flex-basis: 1;
    font-size:2rem;

    span {
      font-weight: bold;
    }
  }

  &--search {
    flex-basis: 2;

    input {
      vertical-align: middle;
      width:200px;
    }
  }

  &--menu{
    flex-basis: 1;
  }
}
</style>
