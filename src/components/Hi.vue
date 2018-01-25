<template>

    <div>
      <p>{{msg}}</p>
      <router-view class="aaa"></router-view>
    </div>
     
</template>

<script>
export default {
  name: 'Hi',
  data () {
    return {
      msg: 'Welcome to Hi'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
