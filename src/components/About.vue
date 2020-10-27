<template>
  <section class="about">
   
    <div class="about-content">
      <img src="../assets/abisai.jpeg" alt="">
      <h1>Abisai Santos</h1>
      <h2>Desenvolvedor Mobile e Web</h2>
      <h3>Programador Mobile e Web, apaixonado pelo front-end. <br>Sempre em busca de desafios que me levem a novos aprendizados.
      <font-awesome-icon style="color:#0e2431;" :icon = "['fas', 'rocket']" /> </h3>
      
    </div>
    <div class="redes-sociais">
      <a href="https://github.com/AbisaiSan" target="_blank"><font-awesome-icon class="icon" style="color:#0e2431;" :icon = "['fab', 'github']" size="2x"   /></a>
      <a href="https://www.linkedin.com/in/abisai-santos/" target="_blank"><font-awesome-icon class="icon" style="color:#0e2431;" :icon = "['fab', 'linkedin']" size="2x"/></a>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>

/*===INFORMAÇÕES INICAIS===*/

.about {
  margin-top: 5%;
  text-align: center;
}

.about img {
  margin-top: 2%;
  text-align: center;
  width: 190px;
  height: 190px;
  border-radius:50%;
  border: 3px solid var(--color-secundaria);
}


.about-content h1{
  font-size: 2.5em;
  line-height: 35px;
  font-weight: 500;
  color:var(--color-secundaria);
  
}
.about-content h2 {
  font-size: 1.5em;
  line-height: 35px;
  font-weight: bold;
  color:var(--color-principal);

  
}
.about-content h3 {
  font-size: 1.3em;
  line-height: 25px;
  color:(--color-principal);
  text-align: justify;
  padding: 3% 4%;
}


.icon{
  padding: 1%;
}
.redes-sociais i:hover{
  color: (--color-secundaria) !important;
  transition: color 300ms !important;
}
</style>