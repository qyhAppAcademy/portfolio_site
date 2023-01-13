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
                Implemented CRUD functionalities for reviews using a Ruby on Rails RESTful API, JBuilder, and React/Redux to enable users to write a new review on a business, see reviews by all users, and edit or delete their reviews.
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
                Utilized D3.js to construct a world map, a bar chart, and a range slider, bind trade data to them and apply DOM manipulation in the world map and the bar chart when a user selects a particular range.
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
                Led the creation and integration of an Express RESTful API, Redux reducers, and React components, to achieve CRUD functionalities.
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
