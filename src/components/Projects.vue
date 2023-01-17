<template>
  <div class="tokyo_tm_contact">
    <div class="tokyo_tm_title">
      <div class="title_flex">
        <div class="left">
          <span>Projects</span>
          <h3>My Recent Work</h3>
        </div>
      </div>
    </div>
    <!-- End Title -->

    <ul class="projects">
      <li class="project">
        <img src="../assets/img/portfolio/qelp.png" alt="qelp" />
        <div class="description-container">
          <div class="description">
            <div class="description-title">
              <a
                href="https://qelp.onrender.com/"
                target="_blank"
                rel="noreferrer"
              >Qelp</a>
              <a
                href="https://github.com/qyhAppAcademy/qelp"
                target="_blank"
                rel="noreferrer"
              ><img
                class="svg"
                :src='require("../assets/img/portfolio/github-repo.svg")'
                alt="repo"
              /></a>
            </div>
            <div class="description-technologies">
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
                Developed a RESTful API in a Ruby on Rails backend, and utilized React/Redux to retrieve or upload data in the frontend to achieve CRUD functionalities for reviews.
              </li>
            </ul>
          </div>
        </div>
      </li>
      <li class="project">
        <img
          src="../assets/img/portfolio/portugal_trade_data_visualization.png"
          alt="portugal_trade_data_visualization"
        />
        <div class="description-container">
          <div class="description">
            <div class="description-title">
              <a
                href="https://qyhappacademy.github.io/portugal_trade_data_visualization/"
                target="_blank"
                rel="noreferrer"
              >Portugal Trade Data Visualization</a>
              <a
                href="https://github.com/qyhAppAcademy/portugal_trade_data_visualization"
                target="_blank"
                rel="noreferrer"
              ><img
                class="svg"
                :src='require("../assets/img/portfolio/github-repo.svg")'
                alt="repo"
              /></a>
            </div>
            <div class="description-technologies">
              <div class="technology">D3.js</div>
              <div class="technology">JavaScript</div>
              <div class="technology">HTML5</div>
              <div class="technology">CSS3</div>
            </div>
            <ul>
              <li>
                Fetched public Portugal trade data for 2020 using Asynchronous JavaScript (AJAX).
              </li>
              <li>
                Utilized D3.js to display trade data on a world map and a bar chart, and created a range slider for users to filter trade data dynamically.
              </li>
              <li>
                Applied Object Oriented Programming to encapsulate trade data and to separate rendering tasks of a world map and a bar chart.
              </li>
            </ul>
          </div>
        </div>
      </li>
      <li class="project">
        <img src="../assets/img/portfolio/choose_your_news.png" alt="choose_your_news" />
        <div class="description-container">
          <div class="description">
            <div class="description-title">
              <a
                href="https://choose-your-news.onrender.com/"
                target="_blank"
                rel="noreferrer"
              >Choose Your News</a>
              <a
                href="https://github.com/qyhAppAcademy/Choose-Your-News"
                target="_blank"
                rel="noreferrer"
              ><img
                class="svg"
                :src='require("../assets/img/portfolio/github-repo.svg")'
                alt="repo"
              /></a>
            </div>
            <div class="description-technologies">
              <div class="technology">React/Redux</div>
              <div class="technology">Express</div>
              <div class="technology">Node</div>
              <div class="technology">MongoDB</div>
              <div class="technology">AWS</div>
              <div class="technology">HTML</div>
              <div class="technology">CSS3</div>
            </div>
            <ul>
              <li>
                Created a RESTful API in an Express backend, and utilized React/Redux to receive or send data in the frontend to achieve CRUD functionalities for news figures, news groups, and news articles.
              </li>
              <li>
                Utilized NYTimes API to retrieve news articles according to a user’s subscribed figures, filtered and sorted by the relevance of new articles.
              </li>
              <li>
                Reconstructed React components by replacing props with React Hooks to increase rendering speed by 33%, refactored codebase, and reorganized files to ensure extensibility.
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
