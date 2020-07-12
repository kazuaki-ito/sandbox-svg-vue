<template>
  <svg height="100" viewBox="0 0 48 166" fill="none" xmlns="http://www.w3.org/2000/svg">
    <circle cx="24" cy="83" r="24" :fill="color" v-if="circleVisible"/>
    <path d="M21 0H26V166H21V0Z" :fill="color"/>
  </svg>
</template>

<script>
export default {
  name: 'ItemPoint',
  props: ['color', 'circleVisible']
}
</script>

<style scoped>

</style>
