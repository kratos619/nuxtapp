<template>
  <div>
    <TheHeader @sidenavToggle="displaySideNav = !displaySideNav"></TheHeader>
    <TheSidenav :show="displaySideNav" @close="displaySideNav = false"></TheSidenav>
    <nuxt/>
  </div>
</template>

<script>
import TheHeader from "@/components/Navigation/TheHeader";
import TheSidenav from "@/components/Navigation/TheSidenav";
export default {
  components: {
    TheHeader,
    TheSidenav
  },
  data() {
    return {
      displaySideNav: false
    };
  }
};
</script>

<style>
html,
body {
  font-family: "Cute Font", cursive;
}
</style>
