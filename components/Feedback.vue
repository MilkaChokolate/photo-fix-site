<template>
  <div id="feedback" class="page-section feedback">
    <div class="container">
      <div class="text-center text-white feedback-text">
        <h3>Contact us</h3>
        <p>Lorem ipsum dolor sit amet consectetur.</p>
      </div>
      <form id="contactForm" data-sb-form-api-token="API_TOKEN">
        <div class="row align-items-stretch mb-5">
          <div class="col-md-6">
            <div class="form-group">

              <input id="name" class="form-control" type="text" placeholder="Your Name *" data-sb-validations="required">
              <div class="invalid-feedback" data-sb-feedback="name:required">
                A name is required.
              </div>
            </div>
            <div class="form-group">

              <input id="email" class="form-control" type="email" placeholder="Your Email *" data-sb-validations="required,email">
              <div class="invalid-feedback" data-sb-feedback="email:required">
                An email is required.
              </div>
              <div class="invalid-feedback" data-sb-feedback="email:email">
                Email is not valid.
              </div>
            </div>
            <div class="form-group mb-md-0">

              <input id="phone" class="form-control" type="tel" placeholder="Your Phone *" data-sb-validations="required">
              <div class="invalid-feedback" data-sb-feedback="phone:required">
                A phone number is required.
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="form-group form-group-textarea mb-md-0">

              <textarea id="message" class="form-control" placeholder="Your Message *" data-sb-validations="required" />
              <div class="invalid-feedback" data-sb-feedback="message:required">
                A message is required.
              </div>
            </div>
          </div>
        </div>

        <div class="text-center d-flex justify-content-end pb-5">
          <button id="submitButton" class="btn btn-light btn-xl align-items-center align-self-end" type="submit">
            Send Message
          </button>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "Feedback"
}
</script>

<style scoped>

</style>
