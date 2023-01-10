<template>
  <div class="tokyo_tm_contact">
    <div class="tokyo_tm_title">
      <div class="title_flex">
        <div class="left">
          <span>Contact</span>
          <h3>Get in Touch</h3>
        </div>
      </div>
    </div>
    <!-- End Title -->

    <ul class="get_in_touch">
      <li>
        <p>
          I'm currently looking for a full-time position. If you have a job 
          opportunity or questions in general, please feel free to 
          reach me. I am always happy to answer your questions or simply chat!
        </p>
      </li>
      <li>
        <p>
          Email: qyhwork@gmail.com
          <a
            href="mailto:qyhwork@gmail.com"
            target="_blank"
            rel="noreferrer"
          >
            <img
              class="svg"
              :src='require("../assets/img/svg/social/email.svg")'
              alt="email"
            />
          </a>
        </p>
      </li>
      <li>
        <p>
          Phone: (347) 341-3680
          <a
            href="tel:3473413680"
            target="_blank"
            rel="noreferrer"
          >
            <img
              class="svg"
              :src='require("../assets/img/svg/social/phone.svg")'
              alt="phone"
            />
          </a>
        </p>
      </li>
      <li>
        <p>
          Resume:
          <a
            href="resume.pdf"
            target="_blank"
            rel="noreferrer"
          >
            <img
              class="svg"
              :src='require("../assets/img/svg/social/resume.svg")'
              alt="resume"
            />
          </a>
        </p>
      </li>
      <li>
        <p>
          Social:
          <a
            class="get_in_touch_social"
            href="https://www.linkedin.com/in/qiaoyanghan/"
            target="_blank"
            rel="noreferrer"
          >
            <img
              class="svg"
              :src='require("../assets/img/svg/social/linkedin-color.svg")'
              alt="linkedin"
            />
          </a>
          <a
            class="get_in_touch_social"
            href="https://angel.co/u/qiaoyanghan"
            target="_blank"
            rel="noreferrer"
          >
            <img
              class="svg"
              :src='require("../assets/img/svg/social/angellist.svg")'
              alt="angellist"
            />
          </a>
          <a
            class="get_in_touch_social"
            href="https://github.com/qyhAppAcademy"
            target="_blank"
            rel="noreferrer"
          >
            <img
              class="svg"
              :src='require("../assets/img/svg/social/github-color.svg")'
              alt="github"
            />
          </a>
        </p>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    components: {
    },
    data() {
      return {
      };
    },
    methods: {
    },
  };
</script>
