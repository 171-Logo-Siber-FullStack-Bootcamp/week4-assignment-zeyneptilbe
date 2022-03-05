<template>
  <!-- Content Wrapper -->
  <div id="content-wrapper" class="d-flex flex-column">
    <!-- Main Content -->
    <div id="content">
      <TopBarComponent />
      <!-- Begin Page Content -->
    </div>
  </div>
  <!-- End of Content Wrapper -->
</template>

<script>
import TopBarComponent from "./MainContentComponents/TopBarComponent.vue";

export default {
  name: "MainContentComponent",
  components: { TopBarComponent },
};
</script>

<style></style>
