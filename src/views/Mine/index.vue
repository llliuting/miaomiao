<template>
  <div>
    hello mine
  </div>
</template>

<script>
export default {
  // 组件名称
  name: 'Mine',
  data () {
    return {}
  },
}
</script> 

<!--使用了scoped属性之后，父组件的style样式将不会渗透到子组件中-->
<!--达到样式的私有化，不污染全局-->
<style scoped>

</style>
