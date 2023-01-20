<template>
  <div class="number-number number" v-bind:class="rootClassName">
    <span class="number-text">{{ Value }}</span>
  </div>
</template>

<script>
export default {
  name: 'Number',
  props: {
    rootClassName: String,
    Value: {
      type: String,
      default: '1',
    },
  },
}
</script>

<style scoped>
.number-number {
  position: relative;
  background-color: #ffffff;
}
.number-root-class-name {
  background-color: #E8E6DA;
}
.number-root-class-name1 {
  background-color: #D0DFA6;
}
@media(max-width: 479px) {
  .number-number {
    width: 40px;
    height: 40px;
  }
  .number-text {
    font-size: 18px;
    font-style: normal;
    font-weight: 500;
  }
}
</style>
