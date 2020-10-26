<template>
  <header id="cabecalho">
    <h1 id="logo">
      <a>Abisai</a>
    </h1>
    <!-- Note que agora o botão de fechar está fora do link. -->
    <button class="btn-menu" v-on:click="aparecer()">BUT</button>
    
    <nav class="menu">
      <a  class="btn-close">x</a>
      <ul>
        <li><a>Home</a></li>
        <li><a>Sobre</a></li>
        <li><a>Skills</a></li>
        <li><a>Jobs</a></li>
        <li><a>Blog</a></li>
      </ul>
    </nav>
  </header>

</template>

<script>
export default {
methods:{
  aparecer(){
    let open = document.querySelector('.btn-menu');
    let close = document.querySelector('.btn-close');
    let menu = document.querySelector('.menu');

    open.addEventListener('click', function() {
      menu.style.display = 'block';
    });

    close.addEventListener('click', function() {
      menu.style.display = 'none';
    });
  }
}
}
</script>

<style scoped>

#cabecalho {
    width: 100%;
    display: flex;
    background-color: #fff;
    box-shadow: 0 1px 4px rgba(146, 161, 176, .15);
    padding: 0.7% 0.7%;  
}
#logo {
    width: 56px;
    height: 56px;
    float: left;
    background: url(../assets/logo-mobile.png) center center/56px no-repeat;
    font-size: 0;
}
/*===MENU DE NAVEGAÇÃO===*/
.menu {
  display: none;
  width: 100%;
  height: 100%;
  position: fixed;
  background-color:var(--color-principal);
  top: 0;
  left: 0;
}

.btn-menu{
 width: 56px;
 height: 56px;
 float: right !important;
 text-align: center;
 color: #fff;
 border-radius: 56px;
 cursor: pointer;
 background: linear-gradient(to right, #ce2e3c, #da6709);
}

.btn-close {
  font-size: 3em;
  color: #fff;
  float: right;
  cursor: pointer;
  margin-right: 5%;
}

.menu ul {
  width: 100%;
  float: left;
  text-align: center;
}
.menu li {
  padding: 1.5%;
}

.menu li a{
  font-size: 2em;
  color: #fff;
  padding: 1.5%;
}

 .menu ul li a:hover{
  border-bottom: 2px solid #d40e1f;
  transition: color 500ms;
  cursor: pointer;
}
</style>