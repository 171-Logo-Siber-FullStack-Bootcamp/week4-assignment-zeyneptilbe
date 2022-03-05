<template>
  <div id="wrapper">
    <SideBarComponent />
    <MainContentComponent />
  </div>
</template>

<script>
import SideBarComponent from "./components/SideBarComponent.vue";
import MainContentComponent from "./components/MainContentComponent.vue";

export default {
  name: "App",
  components: { SideBarComponent, MainContentComponent },
};
</script>

<style>
@import "../public/css/sb-admin-2.min.css";
@import "../public/css/sb-admin-2.css";
</style>
