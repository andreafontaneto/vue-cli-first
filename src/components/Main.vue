<template>
  <main class="container">
    
    <p>Finora abbiamo imparato...</p>
    <ul>
      <li class="html">HTML</li>
      <li class="css">CSS</li>
      <li class="bootstrap">Bootstrap</li>
      <li class="javascript">Javascript</li>
      <li class="vuejs">Vue Js</li>
    </ul>
    <p class="p2">ma effettivamente...</p>

    <!-- la @ (chiocciola) significa partire dalla cartella "src" -->
    <img src="@/assets/vuejs-241-it-is-incredible.jpeg" alt="vuejs">
    
  </main>
</template>

<script>
export default {
  name: "Main"
}
</script>

<style scoped>

  p {
    text-align: center;
    margin: 30px 0;
  }

  .p2 {
    margin: 270px 0;
  }

  ul {
    list-style: none;
    display: flex;
    justify-content: space-between;
  }

  li {
    font-size: 30px;
    text-transform: uppercase;
  }

  .html{
    color:gray;
  }

  .css{
    color: orangered;
  }

  .bootstrap{
    color: rgb(89, 9, 143);
  }

  .javascript{
    color:orange;
  }

  .vuejs{
    color: rgb(63, 141, 63);
  }

  img {
    width: 100%;
  }


</style>