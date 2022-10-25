<template>
<div class="pricing d-flex align-items-center justify-content-center">
  <div class="container">
    <div class="pricing-table table-responsive">
      <table class="table">
        <thead>
          <tr>
            <th>&nbsp;</th>
            <th>
              Free
              <span class="ptable-star red">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-half-o"></i>
                <i class="fa fa-star-o"></i>
              </span>
              <span class="ptable-price">$0.0</span>
            </th>
            <th class="highlight">
              Basic
              <span class="ptable-star green">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
              </span>
              <span class="ptable-price">$99.0</span>
            </th>
            <th>
              Business
              <span class="ptable-star lblue">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
              </span>
              <span class="ptable-price">$149.0</span>
            </th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><span class="ptable-title"><i class="fa fa-hdd-o"></i> Storage</span></td>
            <td>
            <i class="fa fa-hdd-o red"></i>
              500 MB
            </td>
            <td>
              <i class="fa fa-hdd-o green"></i>
              100 GB
            </td>
            <td>
              <i class="fa fa-hdd-o lblue"></i>
              500 GB
            </td>
          </tr>
          <tr>
            <td><span class="ptable-title"><i class="fa fa-signal"></i> Band Width</span></td>
            <td>
              <i class="fa fa-signal red"></i>
              100 TB
            </td>
            <td>
              <i class="fa fa-signal green"></i>
              500 TB
            </td>
            <td>
              <i class="fa fa-signal lblue"></i>
              1000 TB
            </td>
          </tr>
          <tr>
            <td><span class="ptable-title"><i class="fa fa-shield"></i> Security</span></td>
            <td>
              <i class="fa fa-shield red"></i>
              100% Secure
            </td>
            <td>
              <i class="fa fa-shield green"></i>
              100% Secure
            </td>
            <td>
              <i class="fa fa-shield lblue"></i>
              100% Secure
            </td>
          </tr>
          <tr>
            <td><span class="ptable-title"><i class="fa fa-headphones"></i> Support</span></td>
            <td>
              <i class="fa fa-times red"></i>
              No Support
            </td>
            <td>
              <i class="fa fa-phone green"></i>
              Phone
            </td>
            <td>
              <i class="fa fa-envelope-o lblue"></i>
              E-mail / Phone
            </td>
          </tr>

          <tr>
            <td>&nbsp;</td>
            <td class="bg"><a class="btn text-white" href="#">Sign Up</a></td>
            <td class="bg"><a class="btn text-white" href="#">Sign Up</a></td>
            <td class="bg"><a class="btn text-white" href="#">Sign Up</a></td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "Pricing"
}
</script>

<style scoped>

</style>
