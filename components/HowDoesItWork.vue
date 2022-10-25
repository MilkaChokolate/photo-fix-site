<template>
<div class="howItWork">
  <h1>How does it work?</h1>

  <div class="howItWork-1 d-flex justify-content-center flex-wrap align-items-center">
    <div class="col-lg-5 col-md-5 col-sm-5 d-flex align-items-center justify-content-center">
     <img src="../static/howWork1.png" class="col-lg-8 col-md-12 col-sm-12">
    </div>
    <div class="col-lg-5 col-md-5 col-sm-5">
      <h2>The first-ever Chrome extension that gives you an untraceable identity.</h2>
      <p>Create a wallet, receive a backup seed key,
        deposit your crypto $$$ and let automation do the rest - we'll mix your funds with the pool
        of coins in Blank to hide their origin.
      </p>
      <p>Each time you want to make a withdrawal,
        Blank will create a new wallet address for you with the amount of crypto $$$ that you requested.
      </p>
    </div>
  </div>

  <div class="howItWork-2 d-flex justify-content-center flex-wrap align-items-center">
    <div class="col-lg-5 col-md-5 col-sm-5">
      <h2>Metamask x Tornado Cash</h2>
      <p>Your funds go into the smart contract as yours but they exit named Blank.
        We use cryptographic proofs to guarantee that no one can link your withdrawals to deposits,
        unless you want them to. In technical language, we use the zkSnark technology to do it.
        Only the user gets the secret to a given deposit, which allows to withdraw the correlating funds from Blank under a new address.
      </p>
      <ol>
        <li>ETH, WBTC and all ERC-20 support</li>
        <li>ETH, WBTC and all ERC-20 support</li>
        <li>Partial Withdraw</li>
      </ol>
    </div>
    <div class="col-lg-5 col-md-5 col-sm-5 d-flex align-items-center justify-content-center">
      <img src="../static/howWork2.png" class="col-lg-8 col-md-12 col-sm-12">
    </div>
  </div>

  <div class="howItWork-3 d-flex justify-content-center align-items-center flex-wrap">
    <div class="col-lg-5 col-md-5 col-sm-5 d-flex align-items-center justify-content-center">
     <img src="../static/howWork3.png" class="col-lg-8 col-md-12 col-sm-12">
    </div>
    <div class="col-lg-5 col-md-5 col-sm-5">
      <h2>The first-ever Chrome extension that gives you an untraceable identity.</h2>
      <p>Create a wallet, receive a backup seed key,
        deposit your crypto $$$ and let automation do the rest - we'll mix your funds with the pool
        of coins in Blank to hide their origin.
      </p>
      <ol>
        <li>ETH, WBTC and all ERC-20 support</li>
        <li>ETH, WBTC and all ERC-20 support</li>
        <li>Partial Withdraw</li>
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
