<template>
  <div class="home container">
    <h1>Hello, World!</h1>
    <h2>Mohan Bonam</h2>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
  }
}
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  background-color: rgb(184, 132, 132);
  justify-content: center; 
  align-content: center;
  height: 100vh;
}

</style>
