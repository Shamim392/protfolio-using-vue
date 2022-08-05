<template>
  <div class="sticky-top">
    <nav class="navbar navbar-expand-lg bgColor">
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarTogglerDemo01"
        aria-controls="navbarTogglerDemo01"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse mt-2 mb-2" id="navbarTogglerDemo01">
        <!-- <img src="../assets/logo.png" className="logo" alt="brand" /> -->
        <ul class="navbar-nav ms-auto mt-2 mt-lg-0">
          <li class="nav-item active">
            <a class="nav-link" href="#/">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#/about">About</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#/skill">Skill</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#/achievement">Achievement</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#/project">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#/project">Blog</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
  name: "myHeader",
};
</script>

<style>
.logo {
  height: 78px;
  width: 258px;
}
.bgColor {
  background-color: #122036;
}
.navbar-toggler {
  color: none !important;
}
.navbar-toggler {
  border: 2px solid white !important;
}

.navbar-brand {
  color: white !important;
}
.nav-link {
  color: white !important;
  font-size: 20px !important;
}

.navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 32 32' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255,102,203, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 8h24M4 16h24M4 24h24'/%3E%3C/svg%3E") !important;
}
</style>
