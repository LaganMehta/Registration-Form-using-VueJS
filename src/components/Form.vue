<template>
  <div class="form">
    <h1>Welcome to Form Page</h1>
    <br>
	<input v-model="message" placeholder="Enter Name" />
  <br>
  <p>Your Name is: {{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: ''
    }
  }
}
</script>

<style>
@media (min-width: 1024px) {
  .h1 {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
