<template>
  <div class="q-ma-xl q-py-xl">
    <div class="row">
      <div class="col-sm-3 col-xs-12 q-mb-lg">
        <div class="text-h6 text-uppercase q-mb-md">Company</div>
        <div class="text-body1 q-mb-md">About</div>
        <div class="text-body1 q-mb-md">Press</div>
        <div class="text-body1 q-mb-md">Blog</div>
      </div>
      <div class="col-sm-3 col-xs-12 q-mb-lg">
        <div class="text-h6 text-uppercase q-mb-md">Partners</div>
        <div class="text-body1 q-mb-md">Advertise</div>
        <div class="text-body1 q-mb-md">Affilate</div>
        <div class="text-body1 q-mb-md">Career</div>
      </div>
      <div class="col-sm-3 col-xs-12 q-mb-lg">
        <div class="text-h6 text-uppercase q-mb-md">Support</div>
        <div class="text-body1 q-mb-md">Help Centre</div>
        <div class="text-body1 q-mb-md">Contact Us</div>
        <div class="text-body1 q-mb-md">Terms & Privacy</div>
      </div>
      <div class="col-sm-3 col-xs-12 q-mb-lg">
        <div class="text-h6 text-uppercase q-mb-md">Subscribe</div>
        <q-input outlined placeholder="Email Address" dense>
          <template v-slot:append>
            <q-btn unelevated color="primary" class="submit-button">Submit</q-btn>
          </template>
        </q-input>
        <div class="q-gutter-md q-mt-lg">
          <q-icon name="mdi-facebook" size="sm"></q-icon>
          <q-icon name="mdi-instagram" size="sm"></q-icon>
          <q-icon name="mdi-twitter" size="sm"></q-icon>
          <q-icon name="mdi-youtube" size="sm"></q-icon>
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.submit-button {
  height: 40px;
  position: relative;
  left: 11px;
}
</style>
