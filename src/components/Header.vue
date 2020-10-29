<template>
  <header class="cabecalho">
     <a href=""><img src="../assets/4.png" alt=""></a>
       
    <nav class="menu">
        <li><a>Home</a></li>
        <li><a>Sobre</a></li>
        <li><a>Skills</a></li>
        <li><a>Jobs</a></li>
        <li><a>Blog</a></li>
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
  },
  
}

}
</script>

<style scoped>

header {
    background-color: #fff;
    box-shadow: #243B55;
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 15px 30px;
}
header nav {
  display: flex;
}
header img {
  width: 200px;
  margin-right:65px;
}
header li a{
  color: var(--color-principal);
  font-size: 1.2rem;
  font-weight: 500;
}
header li a:hover{
  border-bottom: 3px solid var(--color-secundaria);
}
header li {
  margin: 0 15px;
}
header li:first-child{
  margin-left: 0;

}
header li:last-child{
  margin-right: 0;
}

@media (max-width:700px){
  header{
   flex-direction: column;
  }
  header img {
    margin-right: 0;
    margin-bottom: 15px;
  }
}
</style>