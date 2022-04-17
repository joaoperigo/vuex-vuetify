<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Counter />
    <CounterSquared />
    <Buttons />
    <ColorCode />
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  components: {
    'Counter': require('@/components/Counter.vue').default,
    'CounterSquared': require('@/components/CounterSquared.vue').default,
    'Buttons': require('@/components/Buttons.vue').default,
    'ColorCode': require('@/components/ColorCode.vue').default
  }
}
</script>

<style>
  div {
    margin-bottom: 10px;
  }
  .counter {
    font-size: 80px;
  }
  .buttons button {
    font-size: 40px;
    width: 100px;
    margin: 0 10px;
  }
</style>
