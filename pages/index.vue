<template>
  <div
    class="p-6 max-w-lg mx-auto bg-white rounded-xl shadow-md flex items-center space-x-4"
  >
    <Logo />
    <div class="flex flex-row">
    <h1 class="text-lg">DAROACHNET</h1>
    </div>
    <div class="flex flex-row">
      <NuxtLink
        to="/home"
        class="flex w-auto bg-red-600 rounded-md px-4 py-2 text-white hover:bg-white hover:border-red-600 hover:border-2 hover:text-red-600"
      >
        Enter Page
      </NuxtLink>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  layout: "landing",
});
</script>

<style></style>
