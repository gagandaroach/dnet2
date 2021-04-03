<template>
  <div class="">
    <div>
      <img class="object-scale-down" src="/donuts.gif" />
    </div>
    <div class="my-4">
      <h1 class="text-3xl">daroach.net</h1>
      <h1 class="text-base">
        You have used the power of the internet to connect to Gagan's personal
        server.
      </h1>
    </div>
    <div class="mt-3">
      <NuxtLink
        to="/home"
        class="w-52 bg-black rounded-lg px-4 py-2 text-white hover:bg-white hover:border-red-900 hover:border-2 hover:text-red-900"
      >
        Enter Site
      </NuxtLink>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default { layout: "fullscreen" };
</script>

<style></style>
