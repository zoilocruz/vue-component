<template>
  <p>{{ copyright }}</p>
</template>

<script>
export default {
  name: 'Footer',
  data: function () {
    return {
      copyright: 'Copyright 2018 Vue sample'
    }
  }
}
</script>

<style scoped>
footer{
  background: #222;
  padding: 6px;
}
p{
  color: lightgreen;
  text-align: center;
}
</style>
