<template>
  <section>
    <div className="home-section" id="home">
      <Container className="home-content">
        <div className="home-header">
          <p className="heading">Hi There! I am</p>
          <h1 className="heading-name">Shaminur Rahaman</h1>
          <h3 className="heading-content">Front End Developer</h3>
          <ul>
            <li className="first-li">Web Developer</li>
            <li>Competative Programmer</li>
          </ul>
          <div className="btn-div">
            <button type="button" className="button" target="_blank">
              Get Resume
            </button>
            <button type="button " className="button button1">About me</button>
          </div>
        </div>
      </Container>
    </div>
  </section>
</template>

<script>
export default {
  name: "myAbout",
};
</script>

<style>
.home-header {
  padding-left: 220px;
  padding-top: 100px;
}

.home-section {
  position: relative;
  z-index: -1;
  background-position: top center;
  background-repeat: no-repeat;
  background-color: #111a28;
  padding-bottom: 30px !important;
  /* padding-top: 30px !important; */
}

.home-content {
  padding: 8rem 0 2rem !important;
  color: whitesmoke;
  text-align: left;
}

.heading {
  font-size: 22px;
  color: #00cf5d;
}
.heading-name {
  font-size: 82px;
  font-weight: 800;
  margin-bottom: 25px;
  margin-top: -15px;
}
.heading-content {
  margin-top: -15px;
  color: #00cf5d;
}
.first-li {
  list-style: none;
  margin-left: -30px;
}
ul {
  display: flex;
  margin-bottom: 25px;
  margin-top: 10px;
}
ul li {
  position: relative;
  margin-right: 25px;
  margin-top: -7px;
  color: rgba(255, 255, 255, 0.85);
}

ul li:before {
  position: absolute;
  content: "";
  left: -15px;
  top: 10px;
  width: 8px;
  height: 8px;
  border-radius: 10px;
}

ul li:first-child:before {
  display: none;
}
@media only screen and (max-width: 991px) {
  .heading-name {
    font-size: 52px !important;
  }
}
@media only screen and (max-width: 768px) {
  .home-header {
    padding-left: 0;
    text-align: center;
  }
  .heading {
    font-size: 18px;
  }
  .heading-name {
    font-size: 50px !important;
  }
  h3 {
    font-size: 22px;
  }
  ul {
    justify-content: center;
  }

  ul li {
    font-size: 15px;
  }
}
@media only screen and (max-width: 500px) {
  .heading {
    font-size: 16px;
  }

  .heading-name {
    font-size: 36px !important;
  }

  .h3 {
    font-size: 20px;
  }

  ul li {
    font-size: 14px;
  }

  ul li:before {
    display: none;
  }
}

/* Button section css start */
.btn-div {
  margin-bottom: 20px;
}
.button {
  background-color: #00cf5d;
  color: white;
  transition-duration: 0.4s;
  padding: 14px 25px 14px 25px;
  border: none;
  border-radius: 4px;
  margin-right: 25px;
  margin-top: 10px;
  cursor: pointer;
}

.button1 {
  background-color: #111a28;
  color: white;
  border: 2px solid #4caf50;
}
</style>
