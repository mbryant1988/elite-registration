<template>
  <div class="regForm">

    <iframe class="frame" src="https://docs.google.com/forms/d/e/1FAIpQLSe4uddTq24Is4bUXS32HC4il4_4gobBs5RETN9pIWTS-6VbFA/viewform?embedded=true" width="640" height="3200" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
</div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.frame{
  width: 100%;
}
.regForm {

  padding-top: 120px;
}
</style>
