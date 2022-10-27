<template>
  <header id="header">
    <h1>喵喵影院</h1>
  </header>
</template>

<script>
export default {
  // 组件名称
  name: 'Header',
  data () {
    return {}
  },
}
</script> 

<!--使用了scoped属性之后，父组件的style样式将不会渗透到子组件中-->
<!--达到样式的私有化，不污染全局-->
<style scoped>
#header{width:100%; height:50px; color: #fff; background: #e54847; border-bottom: 1px solid #e54847; position: relative;}
#header h1{ font-size: 18px; text-align: center; line-height: 50px; font-weight: normal; }
#header i{ position: absolute; left: 5px; top: 50%; margin-top: -13px; font-size: 26px;}
</style>
