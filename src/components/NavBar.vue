<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img class="img-fluid logo" src="@/assets/img/unq.png"/>
      </a>
      <button aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"
              class="navbar-toggler"
              data-bs-target="#navbarSupportedContent" data-bs-toggle="collapse" type="button">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="navbarSupportedContent" class="collapse navbar-collapse">
        <ul class="navbar-nav me-auto ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <RouterLink class="nav-link" to="/">Home</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink class="nav-link" to="/about">About</RouterLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
</script>

<style scoped>
.navbar {
  background: var(--background);
  color: var(--text-color);
  margin-bottom: 30px;
}

.nav-link {
  color: var(--text-color);
}

.nav-link:hover {
  color: var(--site-color);

}

.logo {
  max-height: 42px;
  border-radius: 50%;
}
</style>