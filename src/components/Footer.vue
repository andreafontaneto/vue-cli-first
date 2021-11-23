<template>
  <footer class="container">
    
    <p>Made by <span>Andrea Fontaneto</span></p>
  
  </footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>

  footer {
    height: 70px;
    background-color: black;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  span {
    color: mediumseagreen;
    font-style: italic;
  }

</style>