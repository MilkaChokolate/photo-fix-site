<template>
  <NuxtLayout>
    <About></About>
    <HowDoesItWork></HowDoesItWork>
    <Pricing></Pricing>
    <Feedback></Feedback>
    <Footer></Footer>
  </NuxtLayout>

</template>

<script>
import HowDoesItWork from "../components/HowDoesItWork";
export default {
  name: 'IndexPage',
  components: { HowDoesItWork }
}
</script>
