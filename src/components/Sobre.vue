<template>
   <div class="sobre">
    <h1 class="title-sobre">Sobre</h1>
    <div class="sobre-content">
      <img id="img-sobre" src="../assets/abisai.jpeg" alt="">
      <p  class="sobre-text">Sou formado em Analise e Desenvolvimento de Sistemas. 
        Trabalho como desenvolvedor de software desde 2017, tenho amplo conhecimento em linguagens 
        PHP e Javascript. 
        Já trabalhei com frameworks (Laravel, React, Vue.js) web e mobile. Gosto de planejar, resolver problemas 
        e criar soluções que tragam uma boa experiência ao usuário. 
        Sou apaixonado pelo front-end e a cada dia busco me tornar melhor no que faço.</p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>

/*===Sobre===*/

.sobre{
  margin-top: 5%;
  text-align: center;
}
.title-sobre{
  font-size: 38px;
  line-height: 48px;
  color: #4070f4;
}

.sobre-content {
  margin-top: 3%;
  display: grid;
  grid-template-columns: 1fr 1fr;
  justify-content: space-around;
}

#img-sobre {
  width: 250px;
  height: 240px;
  border-radius: 10%; 
}

.sobre-text {
  text-align: justify;
  font-size: 18px;
  line-height: 28px;
}
</style>