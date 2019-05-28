<template>
  <section class="container">
    <Navbar></Navbar>
    <div class="hero-section">
        <h1>Student</h1>
        <h1>Tech Enthusiast</h1>
    </div>
    <AboutMe></AboutMe>
    <!-- <div class="transition-bar"></div> -->
    <Timeline></Timeline>
    <div class="hero-section-concordia">
        <a name="education"><h1>Education</h1></a>
        <h2>B.Eng Software Engineering Co-op</h2>
        <h2 style="font-weight:500">Concordia University</h2>
        <h3 style="margin-top:-1vh">Montreal, Quebec</h3>
        <h3 style="margin-top: 2vh">September 2016 - May 2020 (expected)</h3>
    </div>
    <div class="headerExtra">
        <a name="extracurriculars"><h1>Extracurriculars</h1></a>
    </div>
    <Extracurricular></Extracurricular>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import Navbar from '~/components/Navbar.vue'
import AboutMe from '~/components/AboutMe.vue'
import Timeline from '~/components/Timeline.vue'
import Extracurricular from '~/components/Extracurricular.vue'
export default {
  components: {
    AppLogo,
    Navbar,
    AboutMe,
    Timeline,
    Extracurricular,
  }
}
</script>

<style>
h1 {
  font-family: 'Oswald', sans-serif;
  letter-spacing: 1.5px;
  color: #ffffff;
  font-weight: 100;
  font-size: 2.4em;
  padding-bottom: 2vh;
  text-shadow: 2px 4px 4px #0a0a0a;
}
.title {
  font-family: 'Oswald', sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
.hero-section {
  background: url("../assets/Cover_Image.jpg") 50% no-repeat;
  opacity: inherit;
  /* background: linear-gradient(135deg, rgba(0,0,0,0), rgba(0,0,0,0), 80%, black); */
  background-size: cover;
  height: 93.5vh;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap-reverse;
  box-shadow: inset -20vh -20vh 20vh -20vh rgba(0, 0, 0, 1);
}

.hero-section h1 {
  font-family: 'Source Sans Pro', 'Oswald', sans-serif;
  color: #EBE8E4;
  text-align: right;
  font-weight: 200;
  text-shadow: 2px 4px 4px #0a0a0a;
  padding-top: 3vh;
  padding-right: 4vw;
  font-size: 3em;
  background: linear-gradient(135deg, rgba(0,0,0,0), rgba(0,0,0,0), 80%, black);
  background-color: rgba(0, 0, 0, 0.);
}
.hero-section-concordia {
  background: url("../assets/concordia.jpg") 50% no-repeat;
  opacity: inherit;
  font-family: 'Source Sans Pro', 'Oswald', sans-serif;
  /* background: linear-gradient(135deg, rgba(0,0,0,0), rgba(0,0,0,0), 80%, black); */
  background-size: cover;
  height: 50.5vh;
  font-display: -apple-system;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap-reverse;
  box-shadow: inset -20vh -20vh 20vh -20vh rgba(0, 0, 0, 1);
}

 .hero-section-concordia h1 {
  font-family: 'Source Sans Pro', 'Oswald', sans-serif;
  color: #ffffff;
  font-weight: 100;
  font-size: 2.4em;
  text-align: left;
  text-shadow: 2px 4px 4px #0a0a0a;
  padding: 2vh 4vh 2vh 4vw;
  margin-bottom: 8vh;
  background: linear-gradient(-135deg, rgba(0,0,0,0), rgba(0,0,0,0), 80%, black);
  background-color: rgba(0, 0, 0, 0.);
}
 .hero-section-concordia h2 {
  font-family: 'Oswald', sans-serif;
  color: #ffffff;
  font-weight: 100;
  font-size: 1.6em;
  text-align: left;
  text-shadow: 2px 4px 4px #0a0a0a;
  margin-bottom: 1vh;
  padding: 1vh 4vh 1vh 4vw;
  background: linear-gradient(-135deg, rgba(0,0,0,0), rgba(0,0,0,0), 80%, black);
  background-color: rgba(0, 0, 0, 0.);
}
 .hero-section-concordia h3 {
  font-family: 'Oswald', sans-serif;
  color: #ffffff;
  font-weight: 100;
  font-size: 1em;
  text-align: left;
  text-shadow: 2px 4px 4px #0a0a0a;
  padding-left: 4vw;
  background: linear-gradient(-135deg, rgba(0,0,0,0), rgba(0,0,0,0), 80%, black);
  background-color: rgba(0, 0, 0, 0.);
}
.transition-bar {
    height: 8vh;
    background: #EBE8E4;
    box-shadow: inset -5px -5px 5px -5px rgba(0, 0, 0, 1);
    background: linear-gradient(180deg, rgba(255,255,255,1), rgba(255,255,255,1), 80%, rgb(35,35,35));
    text-align: left;
}
.transition-bar > h2 {
    padding: 0.75vw 2vw;
    color: #aaa;
    font-weight: bold;
    
}
</style>

