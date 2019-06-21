<template>
  <div>
    <a href="#" @click.prevent="triggle">Triggle</a>
  </div>
</template>

<script>
  export default {
    methods: {
      triggle (e) {
        console.log(e)
      }
    }
  }
</script>
