<template>
  <div id="feedback" class="page-section feedback">
    <div class="container">
      <div class="text-center text-white feedback-text">
        <h2>Связаться с нами</h2>
        <h6>Если у вас возникли вопросы по приложению или рекомендации по его улучшению,
          то вы можете написать об этом нам здесь.</h6>
      </div>
      <form id="contactForm" data-sb-form-api-token="API_TOKEN">
        <div class="row align-items-stretch mb-5">
          <div class="col-md-6">
            <div class="form-group">

              <input id="name" class="form-control" type="text" placeholder="Имя *" data-sb-validations="required">
              <div class="invalid-feedback" data-sb-feedback="name:required">
                Пожалуйста, укажите имя.
              </div>
            </div>
            <div class="form-group">

              <input id="email" class="form-control" type="email" placeholder="Почта *" data-sb-validations="required,email">
              <div class="invalid-feedback" data-sb-feedback="email:required">
                Пожалуйста, укажите почту.
              </div>
              <div class="invalid-feedback" data-sb-feedback="email:email">
                Неверная почта.
              </div>
            </div>
            <div class="form-group mb-md-0">

              <input id="phone" class="form-control" type="tel" placeholder="Номер телефона *" data-sb-validations="required">
              <div class="invalid-feedback" data-sb-feedback="phone:required">
                Пожалуйста, укажите номер телефона.
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="form-group form-group-textarea mb-md-0">
              <textarea id="message" class="form-control" placeholder="Комментарий *" data-sb-validations="required" />
              <div class="invalid-feedback" data-sb-feedback="message:required">
                Пожалуйста, напишите что-нибудь.
              </div>
            </div>
          </div>
        </div>

        <div class="text-center d-flex justify-content-end pb-5">
          <button id="submitButton" class="btn btn-light btn-xl align-items-center align-self-end" type="submit">
            Отправить
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
