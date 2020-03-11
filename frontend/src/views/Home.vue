<template>
  <div class="home">
    <NavBarComponent :brand-title="brandTitle" />
  </div>
</template>

<script>
import NavBarComponent from "../components/NavBarComponent.vue";

export default {
  name: "home",
  components: {
    NavBarComponent
  },
  data() {
    return {
      brandTitle: "Movie Review Board"
    };
  }
};
</script>

<style scoped></style>
