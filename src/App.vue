<template>
  <v-app>
    <NavBar />
    <!-- <SideBar /> -->
    <v-content>
      <transition name="fade" mode="out-in" appear>
        <router-view />
      </transition>
    </v-content>
  </v-app>
</template>

<style>
.fade-enter {
  opacity: 0;
}

.fade-enter-active,
.fade-enter-active {
  transition: opacity 0.5s ease-out;
}

.fade-leave-to {
  opacity: 0;
}
</style>

<script>
// import SideBar from './components/SideBar'
import NavBar from './components/NavBar'

export default {
  name: 'App',

  components: {
    // SideBar,
    NavBar
  },

  data: () => ({
    //
  })
}
</script>
