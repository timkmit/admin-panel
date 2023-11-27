<template>
  <q-layout view="1Hh Lpr lFf" class="bg-grey-2 text-dark">
    <SideBar />
    <q-page-container>
      <router-view></router-view>
    </q-page-container>
  </q-layout>
</template>

<script>
import SideBar from './components/SideBar.vue'
  export default {
    components: {SideBar}
  }
</script>