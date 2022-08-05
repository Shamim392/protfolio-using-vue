<template>
  <div class="container-fluid introDiv">
    <div class="row intro">
      <p class="introHeading">LET ME INTRODUCE MYSELF</p>
      <div class="col intro-details">
        <p>
          Hello! I'm Shaminur Rahaman Shamim. I'm a front end web developer
          based in Dhaka,Bangladesh. During the day I work as a Front end
          developer kajkam initiative ltd. and in the evening I work on
          freelance projects and utilize the time to built my own products. I
          spent my leisure hours reading books. Right now I'm also trying a hand
          at Javascript and React JS. I love to learn and explore new areas.
        </p>
      </div>
      <div class="col imgDiv">
        <div>
          <img src="../assets/myImg.png" class="image" alt="avatar" />
        </div>
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
.introDiv {
  position: relative;
  background-color: #111a28;
  color: white;
  /* padding-top: 100px; */
}
.intro {
  padding-right: 100px;
  padding-top: 80px;
  padding-bottom: 80px;
}

.introHeading {
  color: #00cf5d;
  text-align: center;
  padding-left: 80px;
  font-weight: bold;
  font-size: 42px;
}
.intro-details {
  padding-left: 80px;
  padding-top: 80px;
  font-size: 18px;
  text-align: left;
  line-height: 2;
}

.image {
  margin-top: 60px;
  margin-left: 100px;
  width: 50%;
  border-radius: 10px;
  transform: scale(0.95);
  filter: grayscale(1);
  transition: 1s all;
}
.image:hover {
  transform: scale(1);
  filter: grayscale(0);
}

/* @media only screen and (max-width: 991px) {
  .introHeading {
    font-size: 42px;
  }
} */
@media only screen and (max-width: 768px) {
  .intro {
    display: flex;
    flex-direction: column;
    /* padding-right: 10px; */
    padding-top: 80px;
    padding-bottom: 60px;
  }
  .introHeading {
    font-size: 28px !important;
  }
  .intro-details {
    padding-top: 40px;
    font-size: 16px;
    text-align: justify;
    line-height: 2;
  }

  .image {
    display: block;
    margin: auto;
  }
}
@media only screen and (max-width: 500px) {
  .intro {
    display: flex;
    flex-direction: column;
    /* padding-right: 10px; */
    padding-top: 80px;
    padding-bottom: 60px;
  }
  .introHeading {
    font-size: 20px !important;
  }
  .intro-details {
    padding-top: 40px;
    font-size: 16px;
    text-align: justify;
    line-height: 2;
  }

  .image {
    display: block;
    margin: auto;
  }
}
</style>
