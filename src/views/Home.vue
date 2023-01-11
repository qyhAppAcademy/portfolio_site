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
              alt="homerun"
            />
            <span class="menu_content">About</span></a
          >
          <!-- End Home -->
          <a
            v-on:click="activetab = 2"
            :class="[activetab === 2 ? 'active' : '']"
          >
            <img class="svg" src="../assets/img/svg/skills.svg" alt="avatar" />
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
              alt="briefcase"
            />
            <span class="menu_content">Projects</span></a
          >
          <!-- End Portfolio -->
          <a
            v-on:click="activetab = 5"
            :class="[activetab === 5 ? 'active' : '']"
          >
            <img class="svg" src="../assets/img/svg/contact.svg" alt="mail" />
            <span class="menu_content"> Contact</span></a
          >
          <!-- End Contact -->
        </div>
        <div class="copyright">
          <p>
            &copy; {{ new Date().getFullYear() }}
            Tokyo VueJS<br/>Created by Ib-Themes
          </p>
        </div>
        <!-- End copyright -->
      </div>
    </div>
    <!-- End leftpart -->

    <!-- Start rightpart -->
    <div class="rightpart">
      <div class="rightpart_in">
        <div class="tokyo_tm_section">
          <div class="container">
            <div v-if="activetab === 1" class="tabcontent">
              <Home />
            </div>
            <!-- End Home tabcontent -->
            <div v-if="activetab === 2" class="tabcontent">
              <About />
            </div>
            <!-- End About tabcontent  -->
            <div v-if="activetab === 3" class="tabcontent">
              <Portfolio />
            </div>
            <!-- End Portfolio tabcontent -->
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
  import Home from "../components/Home";
  import About from "../components/About";
  import Portfolio from "../components/Portfolio";
  import Contact from "../components/Contact";
  export default {
    components: {
      Home,
      About,
      Portfolio,
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
