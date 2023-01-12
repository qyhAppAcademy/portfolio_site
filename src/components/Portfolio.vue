<template>
  <div class="tokyo_tm_contact">
    <div class="tokyo_tm_title">
      <div class="title_flex">
        <div class="left">
          <span>Projects</span>
          <h3>Recent Work</h3>
        </div>
      </div>
    </div>
    <!-- End Title -->

    <ul class="projects">
      <li class="project">
        <img src="../assets/img/portfolio/qelp.png" alt="qelp" />
        <div class="description">
          <div class="description-content">
            <div class="description-content-title">
              <a
                href="https://qelp.onrender.com/"
                target="_blank"
                rel="noreferrer"
              >Qelp</a>
            </div>
            <div class="description-content-technologies">
              <div class="technology">React/Redux</div>
              <div class="technology">Ruby on Rails</div>
              <div class="technology">PostgreSQL</div>
              <div class="technology">AWS</div>
              <div class="technology">HTML5</div>
              <div class="technology">CSS3</div>
            </div>
            <ul>
              <li>
                Stored businesses’ photos in the cloud using AWS S3, and displayed photos of each business in an images-slider using React.
              </li>
              <li>
                Designed search algorithms to allow users to efficiently search for businesses by name, category, or address.
              </li>
              <li>
                Utilized Google Autocomplete API to facilitate users’ search-by-address experience, and Google Maps API to locate searched businesses and display a business’s data in a modal when selected.
              </li>
              <li>
                Implemented CRUD functionalities for reviews using a Ruby on Rails RESTful API, JBuilder, and React/Redux to enable users to write a new review on a business, see reviews by all users, and edit or delete their reviews.
              </li>
            </ul>
          </div>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    data() {
      return {
      };
    },
  };
</script>

<style lang="scss" scoped></style>
