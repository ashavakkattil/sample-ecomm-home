<template>
  <q-layout view="lHh Lpr rff">
    <q-header elevated></q-header>
    <q-footer  class="app-footer q-mb-lg">
      <div class="text-center">
        <span>
          <q-img src="../assets/quasar-logo-full.svg" height="100px" width="100px" contain></q-img>
        </span>
        <span class="q-ml-md text-body1 text-capitalize">@2020 Tinse | All rights reserved</span>
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
  color: inherit
}
</style>
