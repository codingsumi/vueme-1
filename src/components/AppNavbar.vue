<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary shadows1 sticky-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img src="@/assets/images/logo.png" class="img-fluid" style="width: 35px !important;" />
        <span>INFINITE</span>
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarColor04"
        aria-controls="navbarColor04"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarColor04">
        <ul class="navbar-nav ms-auto d-flex gap-5">
          <li class="nav-item">
            <RouterLink class="nav-link active" to="/">Home</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink class="nav-link" to="/about">About</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink class="nav-link" to="/services">Services</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink class="nav-link" to="/hire-developers">Hire Developers</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink class="nav-link" to="/careers">Careers</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink class="nav-link" to="/event-gallery">Event Gallery</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink class="nav-link" to="/get-in-touch">Get In Touch</RouterLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
