<template>
  <div class="hello">
    <p>
      <button @click="sub">-</button>
      <span>{{ count }}</span>
      <button @click="add">+</button>
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      count : 0
    }
  },
  methods: {
    sub() { this.count--; },
    add() { this.count++; }
  }
}
</script>

<style scoped>

</style>
