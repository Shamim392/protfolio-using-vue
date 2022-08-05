<template>
  <div class="skillDiv">
    <div class="skillHading">
      <h1>Professional <span class="skill">Skills</span></h1>
    </div>
    <div class="row skillRow">
      <div class="col-10 col-sm-6 col-md-4 col-lg-3 col-xl-2 tech-icons">
        <i class="fa-light fa-c"></i>
      </div>
      <div class="col-10 col-sm-6 col-md-4 col-lg-3 col-xl-2 tech-icons">
        <i class="fa-light fa-c"></i>++
      </div>
      <div class="col-10 col-sm-6 col-md-4 col-lg-3 col-xl-2 tech-icons">
        <i class="fa-brands fa-square-js"></i>
      </div>
      <div class="col-10 col-sm-6 col-md-4 col-lg-3 col-xl-2 tech-icons">
        <i class="fa-brands fa-node"></i>
      </div>
      <div class="col-10 col-sm-6 col-md-4 col-lg-3 col-xl-2 tech-icons">
        <i class="fa-brands fa-react"></i>
      </div>
      <div class="col-10 col-sm-6 col-md-4 col-lg-3 col-xl-2 tech-icons">
        <i class="fa-brands fa-html5"></i>
      </div>
      <div class="col-10 col-sm-6 col-md-4 col-lg-3 col-xl-2 tech-icons">
        <i class="fa-brands fa-css3-alt"></i>
      </div>
      <div class="col-10 col-sm-6 col-md-4 col-lg-3 col-xl-2 tech-icons">
        <i class="fa-brands fa-bootstrap"></i>
      </div>
      <div class="col-10 col-sm-6 col-md-4 col-lg-3 col-xl-2 tech-icons">
        <i class="fa-brands fa-github"></i>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "mySkill",
};
</script>

<style>
.skillDiv {
  background-color: #111a28;
  color: white;
  padding-top: 30px;
  padding-bottom: 40px;
}
.skillRow {
  justify-content: center;
}

.skillHading {
  text-align: center;
  font-size: 32px;
  padding-bottom: 30px;
}
.skill {
  color: #00cf5d;
}

.tech-icons {
  font-size: 4.5em !important;
  margin: 15px !important;
  padding: 10px !important;
  opacity: 0.93 !important;
  border: 1.8px solid #04bf58 !important;
  vertical-align: middle !important;
  text-align: center !important;
  border-radius: 5px !important;
  display: table !important;
  box-shadow: 4px 5px 4px 3px rgba(4, 125, 57, 0.137) !important;
  overflow: hidden !important;
  transition: all 0.5s ease 0s !important;
}

@media only screen and (max-width: 767px) {
  .tech-icons {
    margin: 10px !important;
  }
}
.tech-icons:hover {
  transform: scale(1.05) !important;
  overflow: hidden !important;
  /* border: 2.2px solid rgba(197, 115, 230, 0.883) !important; */
  border: 2.2px solid #04bf58 !important;
}
.tech-icon-images {
  padding: 20px !important;
  line-height: 1.6 !important;
}
</style>
