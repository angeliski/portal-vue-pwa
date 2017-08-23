<template>
  <div class="waiting">
    Not yet available

    <button class="btn btn-primary" @click="login()">Access</button>
  </div>
</template>
<script>
import auth from '../login'

export default {
  methods: {
    login () {
      auth.login()
    }
  }
}
</script>
<style scoped>
  .waiting {
    padding: 10px;
    color: #555;
  }
</style>
