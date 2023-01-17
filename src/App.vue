<template>

  <div id="app">
    <button @click="count++">Count: {{ count }}</button>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        count: 0
      }
    }
  }
</script>