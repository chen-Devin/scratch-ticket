<template>
  <div class="hello">
    <div>你猜我多大</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import '../../static/scss.scss';
.hello{
  height: px2Rem(200);
  width: px2Rem(300);
  font-size: px2Rem(24);
  background-color: blue;
}
</style>
