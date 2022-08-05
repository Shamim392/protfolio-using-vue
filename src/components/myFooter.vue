<template>
  <div class="home-about-social">
    <h1 class="foorterHeading">FIND ME ON</h1>
    <p>Feel free to <span className="purple">connect </span>with me</p>
    <ul className="home-about-social-links">
      <li className="social-icons">
        <a
          href="https://github.com/Shamim392"
          target="_blank"
          rel="noreferrer"
          className="icon-colour  home-social-icons"
        >
          <i class="fa-brands fa-github"></i>
        </a>
      </li>
      <li className="social-icons">
        <a
          href="https://twitter.com/shamim392"
          target="_blank"
          rel="noreferrer"
          className="icon-colour  home-social-icons"
        >
          <i class="fa-brands fa-square-twitter"></i>
        </a>
      </li>
      <li className="social-icons">
        <a
          href="https://www.linkedin.com/in/shaminur-rahaman-shamim/"
          target="_blank"
          rel="noreferrer"
          className="icon-colour  home-social-icons"
        >
          <i class="fa-brands fa-linkedin"></i>
        </a>
      </li>

      <li className="social-icons">
        <a
          href="https://www.instagram.com/shaminur_125"
          target="_blank"
          rel="noreferrer"
          className="icon-colour home-social-icons"
        >
          <i class="fa-brands fa-square-instagram"></i>
        </a>
      </li>
    </ul>
  </div>
  <div class="footer-copywright">
    <h3>Copyright © 2022 all rights reserved</h3>
  </div>
</template>

<script>
export default {
  name: "myFooter",
};
</script>

<style>
.foorterHeading {
  font-size: 42px;
}
.home-about-social {
  text-align: center !important;
  padding-top: 50px;
  background-color: #111a28;
  color: white !important;
}

.home-about-social-links {
  justify-content: center !important;
  padding-top: 10px !important;
  display: inline-block !important;
  position: relative !important;
  padding-inline-start: 0 !important;
}

.home-social-icons {
  position: relative !important;
  display: inline-block !important;
  width: 40px !important;
  height: 40px !important;
  text-align: center !important;
  font-size: 1.2em !important;
  line-height: 2em !important;
  background: rgba(255, 255, 255, 0.972) !important;
  border-radius: 50% !important;
  transition: 0.5s !important;
}

.home-social-icons::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border-radius: 50%;
  background: #00cf5d;
  transition: 0.5s;
  transform: scale(0.9);
  z-index: -1;
}

.home-social-icons:hover::before {
  transform: scale(1.1);
  box-shadow: 0 0 15px #00cf5d;
}

.home-social-icons:hover {
  color: #00cf5d;
  box-shadow: 0 0 5px #00cf5d;
  text-shadow: 0 0 2px #00cf5d;
}

.social-icons {
  display: inline-block !important;
  padding-right: 10px;
  padding-left: 15px;
}

.icon-colour {
  color: #047939 !important;
}

.footer-copywright {
  background-color: #111a28;
  color: white;
  text-align: center !important;
  padding-bottom: 20px;
}
</style>
