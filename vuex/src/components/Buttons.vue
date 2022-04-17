<template>
    <div class="buttons">
      <button @click="$store.dispatch('decreaseCounter')">-</button>
      <button @click="$store.dispatch('increaseCounter')">+</button>
    </div>
</template>

<script>
export default {
    name: 'Buttons',
}
</script>

<style>

</style>