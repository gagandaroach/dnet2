<template>
  <div>
    <Landing />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import landing from "~/layouts/landing.vue";

export default Vue.extend({
  components: { landing },
  layout: "landing",
});
</script>

<style></style>
