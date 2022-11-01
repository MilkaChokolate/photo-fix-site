<template>
<div>
  <nav class="navbar navbar-expand-lg" style="background: #E7F1FB; position: fixed; width: 100%; z-index: 100">
    <div class="container-fluid">
      <a href="" class="navbar-brand">
        <img src="../static/Frame.png" style="width: 102px; height: 27px">
      </a>
      <button type="button" class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navbarCollapse">
        <span class="navbar-toggler-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="27" height="27" fill="currentColor" class="bi bi-list" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z"/>
          </svg>
        </span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarCollapse">
        <div class="navbar-nav">
          <nuxt-link :to="{ path: '/',hash:'#about'}" class="nav-item nav-link">Why Blank</nuxt-link>
          <nuxt-link :to="{ path: '/',hash:'#howItWorks'}" class="nav-item nav-link">How it works</nuxt-link>
          <nuxt-link :to="{ path: '/',hash:'#pricing'}" class="nav-item nav-link">Pricing</nuxt-link>
          <nuxt-link :to="{ path: '/',hash:'#feedback'}" class="nav-item nav-link">Feedback</nuxt-link>
        </div>
      </div>
    </div>
  </nav>

  <Nuxt></Nuxt>
</div>
</template>

<script>
export default {
  name: "default",
  methods: {

  }
}
</script>

<style scoped>

</style>
