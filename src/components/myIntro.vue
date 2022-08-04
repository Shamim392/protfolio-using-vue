<template>
  <div class="container">
    <div class="row">
      <div class="col">
        <h1>LET ME <span className="purple"> INTRODUCE </span> MYSELF</h1>
        <p className="home-about-body">
          I fell in love with programming and I have at least learnt something,
          I think… 🤷‍♂️
          <br />
          <br />I am fluent in classics like
          <i>
            <b className="purple"> C, C++ and Javascript. </b>
          </i>
          <br />
          <br />
          My field of Interest's are building new &nbsp;
          <i>
            <b className="purple">Web Technologies and Products </b> and also in
            areas related to{" "}
            <b className="purple">
              Deep Learning and Natural Launguage Processing.
            </b>
          </i>
          <br />
          <br />
          Whenever possible, I also apply my passion for developing products
          with <b className="purple">Node.js</b> and
          <i>
            <b className="purple">
              {" "} Modern Javascript Library and Frameworks
            </b>
          </i>
          &nbsp; like
          <i>
            <b className="purple"> React.js</b>
          </i>
        </p>
      </div>
      <div class="col">
        <img src="../assets/myImg.png" className="img-fluid" alt="avatar" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "myIntro",
};
</script>

<style>
.home-about-section {
  position: relative;
  padding-bottom: 70px !important;
  padding-top: 70px !important;
}

.home-about-description {
  divor: white !important;
  padding-top: 100px !important;
  padding-bottom: 20px !important;
  text-align: center;
}

.home-about-body {
  padding-top: 50px;
  font-size: 1.2em !important;
  text-align: left;
}
</style>
