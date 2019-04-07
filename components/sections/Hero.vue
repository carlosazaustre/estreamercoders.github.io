<template>
  <section>
    <div class="container">
      <h1>EStreamerCoders</h1>
      <h2>Comunidad de Live Coding Streamers de habla hispana</h2>
    </div>
  </section>
</template>

<script>
export default {
  name: 'escode-header'
}
</script>

<style scoped>
section {
  background-color: #c51162;
  color: #fafafa;
  text-align: center;
}
h1 {
  font-size: 3em;
}
.container {
  margin: auto;
  max-width: 800px;
  height: 90vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
</style>

