<template>
<section>
    <div class="sckill-title">
      <h2>Skills</h2>
      <h3>Professional Skills</h3>
    </div>
    <div class="skills">
       <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon instagram" style="color:#0e2431;" :icon = "['fab', 'html5']" size="2x"/>
        </a>
      </li>
       <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon instagram" style="color:#0e2431;" :icon = "['fab', 'css3-alt']" size="2x"/>
        </a>
      </li>
       <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon instagram" style="color:#0e2431;" :icon = "['fab', 'js-square']" size="2x"/>
        </a>
      </li>
       <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon instagram" style="color:#0e2431;" :icon = "['fab', 'node']" size="2x"/>
        </a>
      </li>
       <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon instagram" style="color:#0e2431;" :icon = "['fab', 'react']" size="2x"/>
        </a>
      </li>
      <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon instagram" style="color:#0e2431;" :icon = "['fab', 'laravel']" size="2x"/>
        </a>
      </li>
      <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon instagram" style="color:#0e2431;" :icon = "['fab', 'vuejs']" size="2x"/>
        </a>
      </li>
      <img id="img-skills" src="../assets/skills.jpg" alt="Foto de Lukas no Pexels">
  </div>
</section>
</template>

<script>
export default {

}
</script>

<style scoped>
/*===SKILLS===*/
.skills {
  margin: 5% 15% 0px 15%;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
}

.sckill-title {
  margin-top: 5%;
}

.sckill-title h2 {
  text-align: center;
  font-size: 38px;
  line-height: 48px;
  color: #4070f4;
}
.sckill-title h3 {

  text-align:center;
  font-size: 28px;
  line-height: 38px;
  color: #0e2431;
}

.skills_skills {
    text-decoration: none !important;
    margin-top: 2%;
    align-items: center;
    padding: 0.6rem 1rem;
    border-radius: .5rem;
    box-shadow: 0 4px 25px rgba(14, 36, 49, .15);
}
.skills_skills a {
  text-decoration: none;
  font-size: 15px;
  color:#0e2431;
  font-weight: 500;
}
#img-skills {
  width: 400px;
  height: 300px;
  border-radius: .5rem;
  margin: 1.4rem;
}
.skills_skills:hover{
  -webkit-transform: scale(0);
  transform: scale(1.1);
  transition: all 0.5s;

}


</style>