<template>
  <!-- Topbar Navbar -->
  <ul class="navbar-nav ml-auto">
    <!-- Nav Item - Search Dropdown (Visible Only XS) -->
    <MessagesComponent />
    <AlertComponent />
    <UserComponent />
    <div class="topbar-divider d-none d-sm-block"></div>
  </ul>
</template>

<script>
import MessagesComponent from "./NavbarComponent/MessagesComponent";
import UserComponent from "./NavbarComponent/UserComponent";
import AlertComponent from "./NavbarComponent/AlertComponent";

export default {
  name: "NavBarComponent",
  components: { MessagesComponent, UserComponent, AlertComponent },
};
</script>
