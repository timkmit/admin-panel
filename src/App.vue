<template>
  <q-layout view="1Hh Lpr lFf" class="bg-grey-2 text-dark">
    <SideBar />
    
    <q-page-container>
      <Home/>
      <router-view></router-view>
    </q-page-container>
    
  </q-layout>
</template>

<script>
import SideBar from './components/SideBar.vue'
import Home from './views/Home.vue';
  export default {
    components: { SideBar, Home }
  }
</script>