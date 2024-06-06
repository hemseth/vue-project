<template>
  <!-- ===== Page Wrapper Start ===== -->
  <div class="flex h-screen overflow-hidden">
    <Content></Content>
  </div>
</template>
<script>
import NavBar from "@/components/dashboard/navbar.vue";
import SideBar from "@/components/dashboard/sidebars/sidebar.vue";
import Content from "@/components/dashboard/mains/content.vue";
export default {
  components: {
    Content,
  },
  props: {},
  beforeCreate() {},
  created() {},
  mounted() {},

  data() {
    return {
      task: "",
      todos: [],
    };
  },
  methods: {
    addTodo() {
      this.todos.push(this.task);
    },
    changeColor() {},
  },
};
</script>

<style></style>
