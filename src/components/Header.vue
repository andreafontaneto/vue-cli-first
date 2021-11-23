<template>
  <header class="container">

    <h1>La mia prima app con Vue CLI!</h1>
    <h2>E' il mio primo tentativo, ma è pur sempre un inizio</h2>

  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

  h1 {
    font-size: 50px;
    color: white;
    background-color: mediumseagreen;
    padding: 50px 0;
  }

  h2 {
    font-size: 18px;
    color: mediumseagreen;
    padding: 15px 0
  }

  h1, h2 {
    text-align: center;
  }

</style>