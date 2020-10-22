<template>
  <section class="about">
   
    <div class="about-content">
      <img src="../assets/abisai.jpeg" alt="">
      <h1>Abisai Santos</h1>
      <h2>Desenvolvedor Mobile e Web</h2>
      <h3>Programador Mobile e Web, apaixonado pelo front-end.<br> sempre em busca de desafios que me levem a novos aprendizados 
        <i class="fa fa-rocket" aria-hidden="true"></i></h3>
    </div>
    <div class="redes-sociais">
      <a href="https://github.com/AbisaiSan" target="_blank"> <i style="color:#0e2431;" class="fa fa-linkedin fa-3x" aria-hidden="true"></i></a>
      <a href="https://www.linkedin.com/in/abisai-santos/" target="_blank"><i style="color:#0e2431" class="fa fa-github fa-3x" aria-hidden="true"></i></a>
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
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 5%;
  text-align: center;
}
.about img {
  width: 190px;
  height: 190px;
  border-radius:50%;
  border: 3px solid #4070f4;
}


.about-content h1{
  font-family: 'Roboto', sans-serif;
  margin-top: 1%;
  font-size: 48px;
  line-height: 35px;
  font-weight: 500;
  color: #4070f4;
  
}
.about-content h2 {
  font-family: 'Roboto', sans-serif;
  margin-top: 1%;
  font-size: 28px;
  line-height: 35px;
  font-weight: bold;
  color: #0e2431;

  
}
.about-content h3 {
  font-family: 'Roboto', sans-serif;
  margin-top: 7px;
  font-size: 22px;
  line-height: 25px;
  color: #0e2431;
  text-align: center;
}

.redes-sociais {
margin-top: 5%;

}
.redes-sociais i{
  text-align: end;
  padding: 10px;
}
.redes-sociais i:hover{
  color: #4070f4 !important;
  transition: color 300ms !important;
}
</style>