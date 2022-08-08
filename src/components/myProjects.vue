<template>
  <div class="container-fluid projetDiv">
    <h1 class="proHeading">My Recent <span>Works</span></h1>
    <div class="row projectRow">
      <div class="col-12 col-md-6 col-lg-4 col-xl-4 projectCard">
        <div class="card" style="width: 18rem">
          <img
            class="card-img-top"
            src="../assets/one.png"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">Ecommerce</h5>
            <p class="card-text">
              This is a ecommerce website.In this website anyone can order
              products,create account,login
            </p>
          </div>
          <div class="card-body buttonDIv">
            <a href="https://github.com/Shamim392">
              <button type="button" class="btn btn-success">Github-Link</button>
            </a>
            <a href="https://github.com/Shamim392">
              <button type="button" class="btn btn-success">Demo-Link</button>
            </a>
          </div>
        </div>
      </div>
      <div class="col-12 col-md-6 col-lg-4 col-xl-4">
        <div class="card" style="width: 18rem">
          <img
            class="card-img-top"
            src="../assets/two.png"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">Ecommerce</h5>
            <p class="card-text">
              This is a ecommerce website.In this website anyone can order
              products,create account,login
            </p>
          </div>
          <div class="card-body buttonDIv">
            <a href="https://github.com/Shamim392">
              <button type="button" class="btn btn-success">Github-Link</button>
            </a>
            <a href="https://github.com/Shamim392">
              <button type="button" class="btn btn-success">Demo-Link</button>
            </a>
          </div>
        </div>
      </div>
      <div class="col-12 col-md-6 col-lg-4 col-xl-4">
        <div class="card" style="width: 18rem">
          <img
            class="card-img-top"
            src="../assets/three.jpg"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">Travel-Tour</h5>
            <p class="card-text">
              This project is a Tour management system website.
            </p>
          </div>
          <div class="card-body buttonDIv">
            <a href="https://github.com/Shamim392">
              <button type="button" class="btn btn-success">Github-Link</button>
            </a>
            <a href="https://github.com/Shamim392">
              <button type="button" class="btn btn-success">Demo-Link</button>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "myProjects",
};
</script>

<style>
.projetDiv {
  padding-top: 60px;
  background-color: #111a28;
}
.projectRow {
  justify-content: space-around !important;
  padding-left: 140px;
  padding-right: 80px;
}
.proHeading {
  color: white;
  text-align: center;
  padding-bottom: 50px;
}
span {
  color: #00cf5d;
}

.card-title {
  text-align: center;
  font-weight: bold;
}
.card-text {
  text-align: justify;
}

.card-body > a:not(:last-child) {
  margin-right: 40px;
}
.card-link {
  color: white;
  text-decoration: none;
  pointer-events: none;
}

@media only screen and (max-width: 500px) {
  .projectRow {
    justify-content: space-between;
  }
  .card {
    margin-top: 10px;
    margin-left: -55px;
  }
}
@media only screen and (max-width: 768px) {
  .projectRow {
    justify-content: space-between !important;
  }
  .card {
    margin-bottom: 40px;
  }
}
@media only screen and (max-width: 991px) {
  .projectRow {
    justify-content: space-between !important;
  }
  .card {
    margin-bottom: 40px;
  }
}
</style>
