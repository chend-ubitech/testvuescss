<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <div>hello</div>
  </div>
</template>

<style scoped lang="scss">
.greetings {
  color: $primary-color;
}
</style>
