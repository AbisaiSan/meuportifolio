<template>
  <section class="caracteristicas">
      <div class="grid">
        <img style="" src="../assets/abisai.jpeg" alt="">
        <p >Sou formado em Analise e Desenvolvimento de Sistemas. 
        Trabalho como desenvolvedor de software desde 2017, tenho amplo conhecimento em linguagens 
        PHP e Javascript.
        Já trabalhei com frameworks (Laravel, React, Vue.js) web e mobile. Gosto de planejar, resolver problemas 
        e criar soluções que tragam uma boa experiência ao usuário. 
        Sou apaixonado pelo front-end e a cada dia busco me tornar melhor no que faço.</p>
        
      </div>
  </section>
  
</template>

<script>
export default {

}
</script>

<style scoped>

/*===Sobre===*/
.caracteristicas {
  margin-top: 2%;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 100px 50px;
  background-color: var(--color-principal);
}
.caracteristicas .grid{
  width: 100%;
  display: flex;
  padding: 0 70px;
}

.caracteristicas .grid img {
  width: 220px;
  height: 220px;
  border-radius: 15px;
  display: flex;
  justify-content: center;
  align-items: center;
  
}
.caracteristicas .grid p{
  padding-left: 100px;
  color:var(--color-withe);
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: justify;
}


@media (max-width:850px){
  .caracteristicas .grid {
    flex-direction: column;
     padding: 0;
  }
  .caracteristicas .grid p{
    margin-top: 10%;
    padding-left: 0;
  }
  .caracteristicas .grid img {
    display: flex;
    justify-content: center;
    align-items: center;
  }
}

</style>