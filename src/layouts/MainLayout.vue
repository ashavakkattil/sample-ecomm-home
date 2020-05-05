<template>
  <q-layout view="lHh Lpr rff">
    <q-header elevated></q-header>
    <q-footer  class="app-footer">
      <div class="text-center">
        <span>image</span>
        <span class="q-ml-md">All rights reserved</span>
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
