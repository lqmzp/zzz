<template>
  <div>
    <input type="number" v-model.number="obj.count" />
    <span>{{ obj.goodsName }}</span>
    <span v-show="obj.count == 0">εεδΊ!!!</span>
  </div>
</template>

<script>
export default {
  props: ["obj"],
};
</script>

<style></style>
