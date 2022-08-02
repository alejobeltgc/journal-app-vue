<template>
  <div class="home">
    <img src="/vite.svg" class="logo" alt="Vite logo" />

    <h1>Botones</h1>
    <button @click="goToDaybook" class="btn btn-primary">Primary</button>
    <button @click="goToDaybook" class="btn btn-secondary">Secondary</button>
    <button @click="goToDaybook" class="btn btn-success">Success</button>
  </div>
</template>

<script>
export default {
  methods: {
    goToDaybook() {
      this.$router.push({name: 'no-entry'})
    }
  }
}
</script>