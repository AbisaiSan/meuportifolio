<template>
  <header>
      <div class="links">
        <a id="logo" href="index.html">Abisai</a>
        <a href="index.html">Home</a>
        <a href="">Sobre</a>
        <a href="">Skills</a>
        <a href="jobs.html">Jobs</a>
        <a href="">Blog</a>
      </div>
  </header>

</template>

<script>
export default {

}
</script>

<style scoped>
  header {
    
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    background-color: #fff;
    box-shadow: 0 1px 4px rgba(146, 161, 176, .15);
    padding: 15px 0;  
  }
  #logo {
  margin-right: 80px; /* Alterar essa gambiarra*/
  }
/*===MENU DE NAVEGAÇÃO===*/
.links a {
  font-family: 'Roboto', sans-serif;
  text-decoration: none;
  font-size: 16px;
  color: #0e2431;
  padding: 15px;
}

.links a:hover{
  border-bottom: 2px solid #4070f4;
  transition: color 500ms;
}
</style>