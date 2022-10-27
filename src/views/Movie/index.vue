<template>
  <div id="main">
    <Header />
    <Tabbar />
  </div>
</template>

<script>
import Header from '@/components/Header'
import Tabbar from '@/components/Tabbar'
export default {
  // 组件名称
  name: 'Movie',
  data () {
    return {}
  },
  components: {
    Header,
    Tabbar
  }
}
</script> 

<!--使用了scoped属性之后，父组件的style样式将不会渗透到子组件中-->
<!--达到样式的私有化，不污染全局-->
<style scoped>

</style>
