<template>
  <ul class="social">
    <li v-for="(social, i) in socialList" :key="i">
      <a :href="social.link" target="_blank" rel="noreferrer"
        ><img class="svg" :src="social.src" alt="social"
      /></a>
    </li>
  </ul>
  <!-- End. social -->
</template>

<script>
  export default {
    data() {
      return {
        socialList: [
          {
            link: "https://www.linkedin.com/in/qiaoyanghan/",
            src: require("../assets/img/svg/social/linkedin.svg"),
          },
          {
            link: "https://angel.co/u/qiaoyanghan",
            src: require("../assets/img/svg/social/angellist.svg"),
          },
          {
            link: "https://github.com/qyhAppAcademy",
            src: require("../assets/img/svg/social/github.svg"),
          },
        ],
      };
    },
  };
</script>

<style lang="scss" scoped></style>
