<template>
  <q-layout view="lHh Lpr rff">
    <q-header elevated></q-header>
    <q-footer class="app-footer q-mb-lg">
      <div class="row ">
        <div class="col-xs-12 col-md-6" :class="$q.screen.gt.xs ? 'text-right': 'text-center'">
          <q-img src="../assets/quasar-logo-full.svg" height="100px" width="100px" contain></q-img>
        </div>
        <div class="col-xs-12 col-md-6" :class="$q.screen.gt.xs ? 'text-left': 'text-center'" style="align-self: center">
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
