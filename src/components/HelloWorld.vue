<template>
  <div class="regForm">

    <iframe class="frame" src="https://docs.google.com/forms/d/e/1FAIpQLSfsfHBMLe7HW9IY2tyAMgKxWsal3WAChWvVwfXE1ogyj-yo-A/viewform?embedded=true" width="640" height="3200" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
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
