<template>
  <div>
    <button @click="onChoiceFruit">과일</button>
    <button @click="onChoiceGrain">곡식</button>
    <button @click="onChoiceMap">지도</button>
  </div>
</template>

<script>
export default {
  methods: {
    onChoiceFruit() {
      this.$router.push('/fruit')
    },
    onChoiceGrain() {
      this.$router.push('/grain')
    },
    onChoiceMap() {
      this.$router.push('/map')
    }
  }
}
</script>

<style scoped>

</style>