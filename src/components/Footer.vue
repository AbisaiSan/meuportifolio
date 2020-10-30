<template>
  <footer>
  <a id="eu" href="">Abisai Santos</a>
    <div class="icons-footer"> 
      <li>
         <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon github" style="color:#fff;" :icon = "['fab', 'github']" size="2x"/>
         </a>
         <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon github" style="color:#fff;" :icon = "['fab', 'github']" size="2x"/>
         </a>
         <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon github" style="color:#fff;" :icon = "['fab', 'github']" size="2x"/>
         </a>
         <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon github" style="color:#fff;" :icon = "['fab', 'github']" size="2x"/>
         </a>
      </li>
    </div>
    <div class="copy">copy 2020 copyright all right reserved;</div>
</footer>
</template>

<script>
export default {

}
</script>

<style scoped>
  /*===FOOTER===*/
footer{
  width: 100%;
  padding: 16px;
  margin-top: 10%;
  background-color: #0e2431;
  text-align: center;
}

footer #eu {
  font-size: 32px;
  line-height: 42px;
  font-weight: 500;
  color: #FFFFFF;
  text-decoration: none;
}
.icons-footer li {
    margin-top: 2%;
  list-style: none;
}
.icons-footer   a {
  list-style: none;
  padding:0 15px;
}

.copy{
  margin-top: 2%;
  color: #fff;
  font-weight: 600;
}
</style>