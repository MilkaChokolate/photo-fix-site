<template>
  <div class="footer">
    <div class="bg-primary footer-1 text-white d-flex flex-column justify-content-center align-items-center">

      <div class="slogan col-lg-6 col-md-8 col-sm-10">
        Break free from government & big tech overwatch. Go Blank.
      </div>

      <div class="button-group row col-lg-5 col-md-6 col-sm-8 justify-content-center">
        <button type="button" class="btn text-white col-lg-5 col-md-5 col-sm-5 d-flex align-items-center justify-content-between" style="background: rgba(10, 18, 30, 0.7)">
          <p>Request Early Access</p>
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-down-right" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M14 13.5a.5.5 0 0 1-.5.5h-6a.5.5 0 0 1 0-1h4.793L2.146 2.854a.5.5 0 1 1 .708-.708L13 12.293V7.5a.5.5 0 0 1 1 0v6z"/>
          </svg>
        </button>
        <button type="button" class="btn btn-outline-light col col-lg-5 col-md-5 col-sm-5 d-flex align-items-center justify-content-between"><p>Whitepaper</p>
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-down-right" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M14 13.5a.5.5 0 0 1-.5.5h-6a.5.5 0 0 1 0-1h4.793L2.146 2.854a.5.5 0 1 1 .708-.708L13 12.293V7.5a.5.5 0 0 1 1 0v6z"/>
          </svg>
        </button>

      </div>
    </div>


    <div class="text-white footer-2 d-flex flex-wrap">

      <div class="col-lg-5 col-md-5 col-sm-12">
        <img src="../static/LogoInverse.png" class="logo">
        <h5>Privacy shouldn’t be an “opt-in.”
          Rather, it must be something you could occasionally “opt-out” of on Free Will.
        </h5>
      </div>

      <div class="row col-lg-5 col-md-5 col-sm-12 justify-content-end">
        <div class="col-3 d-flex flex-column align-items-between">
          <h5>Legal</h5>
          <a href="#">Privacy Policy</a>
          <a href="#">Terms & Conditions</a>
        </div>
        <div class="col-3 d-flex flex-column align-items-start">
          <h5>Socials</h5>
          <a href="#">Github</a>
          <a href="#">Telegram</a>
          <a href="#">Linkedin</a>
        </div>
        <div class="col-3 d-flex flex-column align-items-start">
          <h5>Get in touch</h5>
          <p>info@goblank.io</p>
        </div>
      </div>

      <div class="d-flex col-lg-11 col-md-11 col-sm-11">
        <p>Copyright © Blank 2021. All rights reserved.</p>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>

</style>
