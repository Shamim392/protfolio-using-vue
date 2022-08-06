<template>
  <div class="sticky-top">
    <nav class="navbar navbar-expand-lg bgColor">
      <div class="container-fluid">
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarTogglerDemo01"
          aria-controls="navbarTogglerDemo01"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
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
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
  name: "myHeader",
};
</script>

<style scoped>
.bgColor {
  background-color: #122036;
}
.navbar-toggler {
  color: none !important;
}

.navbar-brand {
  color: white !important;
}
.nav-link {
  color: white !important;
  font-size: 20px !important;
  margin-top: 7px;
}

.navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 32 32' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255,102,203, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 8h24M4 16h24M4 24h24'/%3E%3C/svg%3E") !important;
}
</style>
