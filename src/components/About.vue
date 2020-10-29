<template>
  <section class="about">
   
    <div class="about-content">
      <img src="../assets/abisai.jpeg" alt="">
      <h1>Abisai Santos</h1>
      <h2>Desenvolvedor Mobile e Web</h2>
      <p>Programador Mobile e Web, apaixonado pelo front-end. 
        Sempre em busca de desafios que me levem a novos aprendizados 
        <font-awesome-icon  style="color:#0e2431;" :icon = "['fas', 'rocket']" />.
       </p>
    </div>

    <div class="redes-sociais">
      <li>
         <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon github" style="color:#0e2431;" :icon = "['fab', 'github']" size="2x"/>
         </a>
      </li>
      <li>
        <a href="https://www.linkedin.com/in/abisai-santos/" target="_blank">
            <font-awesome-icon class="icon linkedin" style="color:#0e2431;" :icon = "['fab', 'linkedin']" size="2x"/>
        </a>
      </li>
      <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon twitter" style="color:#0e2431;" :icon = "['fab', 'twitter']" size="2x"/>
        </a>
      </li>
      <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon instagram" style="color:#0e2431;" :icon = "['fab', 'instagram']" size="2x"/>
        </a>
      </li>
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
  margin-top: 10%;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.about img {
  margin-top: 2%;
  text-align: center;
  width: 190px;
  height: 190px;
  border-radius:50%;
  border: 3px solid var(--color-border);
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

.redes-sociais {
  list-style: none;
  display: flex;
}

.redes-sociais li {
  margin-bottom: 25px;
  margin-top: 7%;
  padding: 0 15px;
}

.redes-sociais .github:hover {
  color: var(--color-black) !important;
  transition: color 300ms !important;
}

.redes-sociais .linkedin:hover {
  color: var(--color-linkedin) !important;
  transition: color 300ms !important;
}
.redes-sociais .twitter:hover {
  color: var(--color-linkedin) !important;
  transition: color 300ms !important;
}
.redes-sociais .instagram:hover {
  color: var(--color-instagram) !important;
  transition: color 300ms !important;
}

@media (max-width:700px){
  .about img {
  margin-top: 30%;
}
}


</style>