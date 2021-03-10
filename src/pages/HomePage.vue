<template>
  <div class="home container">
    <div class="row mt-5">
      <div class="col text-center">
        <h1>Welcome to Gregslist the collection you would like to <img alt="Vue logo" src="../assets/logo.png" /> iew</h1>
      </div>
    </div>
    <div class="row mt-5">
      <div class="col">
      <button>Cars</button>
      <button>Houses</button>
      <button>Jobs</button>
      </div>
    </div>
  </div>
</template>

<script>
import { reactive } from 'vue'

export default {
  name: 'Home',
  setup() {
    const state = reactive({})
    return {
      state
    }
  },
  components: {
  }
}
</script>
<style scoped>
img {
  height: 1em;
}
</style>
