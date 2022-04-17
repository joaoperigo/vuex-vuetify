<template>
    <div>
      <input v-model="colorCode" placeholder="Input color code" type="text">
    </div>
</template>

<script>
export default {
computed: {
    colorCode: {
      get() {
        return this.$store.state.colorCode
      },
      set(newValue) {
        this.$store.dispatch('setColorCode', newValue)
      }
    }
  },
}
</script>

<style>

</style>