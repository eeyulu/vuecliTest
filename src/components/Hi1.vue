<template>
    <div>{{msg}}-{{$route.params.username}}-{{$route.params.id}}</div>
</template>

<script>
export default {
  name: 'Hi',
  data () {
    return {
      msg: 'Welcome to Hi1'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
