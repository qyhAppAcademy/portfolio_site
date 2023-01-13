<template>
  <div>
    <!-- Start leftpart -->
    <div class="leftpart">
      <div class="leftpart_inner">
        <div class="logo">
          <a
            v-on:click="activetab = 1"
            :class="[activetab === 1 ? 'active' : '']"
          >
            <span>
              Q.Y.H
              <img
                src="../assets/img/logo/lightbulb.svg"
                alt="lightbulb"
              />
            </span>
          </a>
        </div>
        <!-- End .logo -->
        <div class="menu">
          <a
            v-on:click="activetab = 1"
            :class="[activetab === 1 ? 'active' : '']"
          >
            <img
              class="svg"
              src="../assets/img/svg/about.svg"
              alt="about"
            />
            <span class="menu_content">About</span></a
          >
          <!-- End About -->
          <a
            v-on:click="activetab = 2"
            :class="[activetab === 2 ? 'active' : '']"
          >
            <img
              class="svg"
              src="../assets/img/svg/skills.svg"
              alt="skills"
            />
            <span class="menu_content">Skills</span></a
          >
          <!-- End About -->
          <a
            v-on:click="activetab = 3"
            :class="[activetab === 3 ? 'active' : '']"
          >
            <img
              class="svg"
              src="../assets/img/svg/projects.svg"
              alt="projects"
            />
            <span class="menu_content">Projects</span></a
          >
          <!-- End Projects -->
          <a
            v-on:click="activetab = 4"
            :class="[activetab === 4 ? 'active' : '']"
          >
            <img
              class="svg"
              src="../assets/img/svg/experience.svg"
              alt="experience"
            />
            <span class="menu_content">Experience</span></a
          >
          <!-- End Experience -->
          <a
            v-on:click="activetab = 5"
            :class="[activetab === 5 ? 'active' : '']"
          >
            <img
              class="svg"
              src="../assets/img/svg/contact.svg"
              alt="contact"
            />
            <span class="menu_content">Contact</span></a
          >
          <!-- End Contact -->
        </div>
      </div>
    </div>
    <!-- End leftpart -->

    <!-- Start rightpart -->
    <div class="rightpart">
      <div class="rightpart_in">
        <div class="tokyo_tm_section">
          <div class="container">
            <div v-if="activetab === 1" class="tabcontent">
              <About />
            </div>
            <!-- End Home tabcontent -->
            <div v-if="activetab === 2" class="tabcontent">
              <Skills />
            </div>
            <!-- End About tabcontent  -->
            <div v-if="activetab === 3" class="tabcontent">
              <Projects />
            </div>
            <!-- End Projects tabcontent -->
            <div v-if="activetab === 4" class="tabcontent">
              <Experience />
            </div>
            <!-- End Experience tabcontent -->
            <div v-if="activetab === 5" class="tabcontent">
              <Contact />
            </div>
            <!-- End Contact tabcontent -->
          </div>
        </div>
      </div>
    </div>
    <!-- End rightpart -->
  </div>
</template>

<script>
  import About from "../components/About";
  import Skills from "../components/Skills";
  import Projects from "../components/Projects";
  import Experience from "../components/Experience";
  import Contact from "../components/Contact";
  export default {
    components: {
      About,
      Skills,
      Projects,
      Experience,
      Contact,
    },
    data() {
      return {
        activetab: 1,
      };
    },
  };
</script>

<style lang="scss" scoped></style>
