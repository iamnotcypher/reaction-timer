<template>
  <div class="block">
    click me
  </div>
</template>

<script>
export default {
  props: ['delay']
}
</script>

<style scoped>
  .block {
    width: 400px;
    border-radius: 12px;
    background: #0faf87;
    color: #fff;
    text-align: center;
    padding: 100px 0;
    margin: 40px auto;
    cursor: pointer;
  }
</style>