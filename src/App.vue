<template>
  <Navbar></Navbar>
  <Sidebar></Sidebar>
</template>
<script>
import Navbar from "./components/dashboard/navbar.vue";
import Sidebar from "./components/dashboard/sidebars/sidebar.vue";
import Content from "./components/dashboard/mains/content.vue";
export default {
  name: "App",
  components: {
    Sidebar,
    Navbar,
    Content,
  },
};
</script>

<style></style>
