<template>
<div id="howItWorks" class="howItWork">
  <h2 class="text-center">Как работает приложение?</h2>

  <div class="step-1 d-flex justify-content-center flex-wrap align-items-center">
    <div class="col-lg-5 col-md-5 col-sm-5 d-flex align-items-center justify-content-center">
     <img src="../static/howWork1.png" class="col-lg-8 col-md-12 col-sm-12">
    </div>
    <div class="col-lg-5 col-md-5 col-sm-5">
      <h3>The first-ever Chrome extension that gives you an untraceable identity.</h3>
      <h6>Create a wallet, receive a backup seed key,
        deposit your crypto $$$ and let automation do the rest - we'll mix your funds with the pool
        of coins in Blank to hide their origin.
      </h6>
      <h6>Each time you want to make a withdrawal,
        Blank will create a new wallet address for you with the amount of crypto $$$ that you requested.
      </h6>
    </div>
  </div>

  <div class="step-2 d-flex justify-content-center flex-wrap align-items-center">
    <div class="col-lg-5 col-md-5 col-sm-5 d-flex align-items-center justify-content-center">
      <img src="../static/howWork2.png" class="col-lg-6 col-md-8 col-sm-8">
    </div>
    <div class="col-lg-5 col-md-5 col-sm-5 order-first">
      <h3>Metamask x Tornado Cash</h3>
      <h6>Your funds go into the smart contract as yours but they exit named Blank.
        We use cryptographic proofs to guarantee that no one can link your withdrawals to deposits,
        unless you want them to. In technical language, we use the zkSnark technology to do it.
        Only the user gets the secret to a given deposit, which allows to withdraw the correlating funds from Blank under a new address.
      </h6>
      <ol>
        <li>ETH, WBTC and all ERC-20 support</li>
        <li>ETH, WBTC and all ERC-20 support</li>
        <li>Partial Withdraw</li>
      </ol>
    </div>
  </div>

  <div class="step-3 d-flex justify-content-center align-items-center flex-wrap">
    <div class="col-lg-5 col-md-5 col-sm-5 d-flex align-items-center justify-content-center">
     <img src="../static/howWork3.png" class="col-lg-6 col-md-8 col-sm-8">
    </div>
    <div class="col-lg-5 col-md-5 col-sm-5">
      <h3>The first-ever Chrome extension that gives you an untraceable identity.</h3>
      <h6>Create a wallet, receive a backup seed key,
        deposit your crypto $$$ and let automation do the rest - we'll mix your funds with the pool
        of coins in Blank to hide their origin.
      </h6>
      <ol>
        <li>ETH, WBTC and all ERC-20 support</li>
        <li>ETH, WBTC and all ERC-20 support</li>
        <li>Partial Withdraw</li>
      </ol>
    </div>
  </div>

  <div class="step-4 d-flex justify-content-center flex-wrap align-items-center">
    <div class="col-lg-5 col-md-5 col-sm-5 d-flex align-items-center justify-content-center">
      <img src="../static/howWork2.png" class="col-lg-6 col-md-8 col-sm-8">
    </div>
    <div class="col-lg-5 col-md-5 col-sm-5 order-first">
      <h3>Приложение дает возможность создавать отчеты в один клик.</h3>
      <h6>
        Отчеты и направлять их по почте, доступны несколько вариантов оформления отчетов, регулировка отсупов и размера прилагаемых фотографий.
        Также доступпен экспорт отчетов в PDF, Word и Excel
      </h6>
      <ol>
        <li>Заполняете формы в задачах в соответсвии с той информацией, которую хотите видеть в отчете</li>
        <li>Загружаете фотографии</li>
        <li>Выполняете и завершаете поставленные задачи</li>
        <li>Выбираете формат отчета</li>
        <li>Нажимаете кнопку создать отчет</li>
        <li class="text-danger">Получаете готовый отчет</li>
      </ol>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "HowDoesItWork"
}
</script>

<style scoped>

</style>
