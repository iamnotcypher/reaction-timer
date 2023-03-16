<template>
  <div class="reaction-time">
    <p>Reaction time: {{ score }}ms</p>
  </div>
</template>

<script>
export default {
  name: 'Results',
  props: ['score']
}
</script>

<style>

</style>