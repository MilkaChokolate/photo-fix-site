<template>
  <div>
    <nav class="navbar navbar-expand-lg" style="background: #E7F1FB; position: fixed; width: 100%; z-index: 100">
      <div class="container-fluid">
          <a href="#" class="navbar-brand">
              <img src="../static/Frame.png" style="width: 102px; height: 27px">
          </a>
          <button type="button" class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navbarCollapse">
              <span class="navbar-toggler-icon">
                <img src="../static/list.svg" style="width: 27px; height: 27px">
              </span>
          </button>
          <div class="collapse navbar-collapse justify-content-end" id="navbarCollapse">
              <div class="navbar-nav">
                  <a href="#" class="nav-item nav-link">Why Blank</a>
                  <a href="#" class="nav-item nav-link">What blank offers</a>
                  <a href="#" class="nav-item nav-link">How it works</a>
                  <a href="#" class="nav-item nav-link">Blank token</a>
                  <button href="#" class="btn btn-secondary">Token Metrics</button>
              </div>
          </div>
      </div>
    </nav>

    <Nuxt></Nuxt>
  </div>

</template>

<script>
export default {
  name: "default"
}
</script>

<style scoped>
.navbar-nav a {
  color: #455A74;
}
</style>
