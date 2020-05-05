<template>
  <div class="q-ma-xl">
    <div class="row">
      <div class="col-6 q-pa-lg">
        <div class="text-h2 q-my-lg">We help u grow more shopping experience</div>
        <div
          class="q-my-lg"
        >QLayout allows you to configure your views as a 3x3 matrix, containing an optional Header and/or Footer (mostly used for navbar, but can be anything). If you haven’t already,</div>
        <div class="q-my-lg">
          <q-btn color="primary" size="xl">Show me how</q-btn>
          <span class="q-ml-md">Get a free demo</span>
        </div>
        <div class="q-gutter-xl q-my-lg">
          <q-icon name="mdi-netflix" size="xl"></q-icon>
          <q-icon name="mdi-netflix" size="xl"></q-icon>
          <q-icon name="mdi-netflix" size="xl"></q-icon>
          <q-icon name="mdi-netflix" size="xl"></q-icon>
        </div>
      </div>
      <div class="col-6 text-center q-pa-lg">
        <q-img src="../assets/main-img.jpg" width="60%"></q-img>
      </div>
    </div>
    <services-block></services-block>
    <premium-features></premium-features>
    <last-block></last-block>
    <page-footer></page-footer>
    <q-separator />
  </div>
</template>
<script>
import ServicesBlock from "../components/ServicesBlock";
import PremiumFeatures from "../components/PremiumFeatures";
import LastBlock from "../components/LastBlock";
import PageFooter from "../components/PageFooter";
export default {
  components: {
    ServicesBlock,
    PremiumFeatures,
    LastBlock,
    PageFooter
  }
};
</script>
