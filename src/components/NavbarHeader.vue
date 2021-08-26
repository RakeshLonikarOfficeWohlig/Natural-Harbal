<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <div class="nav-img">
          <img src="../assets/herbal.png" class="card-img-top" alt="..." />
        </div>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link to="/" class="nav-link active bg-light"
                >HOME</router-link
              >
            </li>

            <li class="nav-item">
              <router-link to="/shop" class="nav-link">SHOP</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/about" class="nav-link">ABOUT</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/faq" class="nav-link">FAQ</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/contact" class="nav-link">CONTACT</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
