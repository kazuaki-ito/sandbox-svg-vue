<template>
  <div class="home">
    <div class="item-point-wrapper">
      <item-point color="#d6833f" :circle-visible="true"/>
    </div>
    <div class="item-point-wrapper">
      <item-point color="#d6833f" :circle-visible="false"/>
    </div>
    <div class="item-point-wrapper">
      <item-point color="#d9d9d9" :circle-visible="true"/>
    </div>
    <div class="item-point-wrapper">
      <item-point color="#d9d9d9" :circle-visible="false"/>
    </div>
  </div>
</template>

<script>
import ItemPoint from '../components/ItemPoint'

export default {
  name: 'Home',
  components: { ItemPoint }
}
</script>

<style lang="scss" scoped>
.item-point-wrapper {
  margin-bottom: -6px;
}

</style>
