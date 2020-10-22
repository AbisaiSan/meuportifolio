<template>
<div>
    <div class="sckill-title">
      <h2>Skills</h2>
      <h3>Professional Skills</h3>
    </div>
    <div class="skills">
      <div class="skils-content">
          <div class="skills_skills">
            <span style="color:#e44e25" class='bx bxl-html5 bx-md' ></span><a href="">HTML</a>
          </div> 
          <div class="skills_skills">
            <span style="color:#264de4"  class='bx bxl-css3 bx-md' ></span> <a href="">CSS</a>
          </div> 
          <div class="skills_skills">
            <span style="color:#e4a227"  class='bx bxl-javascript bx-md ' ></span><a href="">Javascript</a>
          </div> 
           <div class="skills_skills">
            <span style="color:#e4a227"  class='bx bxl-javascript bx-md ' ></span><a href="">Vue.js</a>
          </div> 
          <div class="skills_skills">
            <span style="color:#61dafb" class='bx bxl-react bx-md' ></span><a href="">React Js</a>
          </div> 
          <div class="skills_skills">
            <span  style="color:#61dafb" class='bx bxl-react bx-md' ></span><a href="">React Native</a>
          </div> 
          <div class="skills_skills">
            <span style="color:#88c040" class='bx bxl-nodejs bx-md' ></span><a href="">Node</a>
          </div>  
        </div>
        <img id="img-skills" src="../assets/skills.jpg" alt="Foto de Lukas no Pexels">
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
/*===SKILLS===*/
.skills {
  margin-top: 5%;
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

  text-align: left;
  font-size: 28px;
  line-height: 38px;
  color: #0e2431;
}

#img-skills {
  width: 400px;
  height: 300px;
  border-radius: .5rem;
  margin: 9px;
}
.skills_skills {
    text-decoration: none !important;
    margin-top: 2%;
    display: flex;
    align-items: center;
    position: relative;
    padding: .5rem 1rem;
    border-radius: .5rem;
    box-shadow: 0 4px 25px rgba(14, 36, 49, .15);
}
.skills_skills:hover{
  -webkit-transform: scale(1.1);
  transform: scale(1.1);
  transition: all 0.5s;

}
.skills_skills a {
  text-decoration: none;
  font-size: 15px;
  color:#0e2431;
  font-weight: 500;
}

</style>