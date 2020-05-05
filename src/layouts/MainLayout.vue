<template>
  <q-layout view="lHh Lpr rff">
    <q-header elevated></q-header>
    <q-footer class="app-footer q-mb-lg">
      <div class="row" v-if="$q.screen.xs">
        <div class="col-12 text-center">
          <q-img src="../assets/quasar-logo-full.svg" height="100px" width="100px" contain></q-img>
        </div>
        <div class="col-12">
          <div class="text-body1 text-capitalize text-center">@2020 Tinse | All rights reserved</div>
        </div>
      </div>
      <div class="row" v-else>
        <div class="col-6 text-right">
          <q-img src="../assets/quasar-logo-full.svg" height="100px" width="100px" contain></q-img>
        </div>
        <div class="col-6 text-left" style="align-self: center;">
          <div class="text-body1 text-capitalize">@2020 Tinse | All rights reserved</div>
        </div>
      </div>
    </q-footer>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  name: "MainLayout",

  components: {},

  data() {
    return {};
  }
};
</script>
<style lang="scss" scoped>
.app-footer {
  background-color: transparent;
  color: inherit;
}
</style>
