<script setup>
import Ghost from "./components/Ghost.vue";
</script>

<template>
  <main class="grid place-items-center h-screen">
    <div class="relative">
      <div
        class="bg-gradient-to-r from-purple-900 to-blue-900 p-20 rounded-full blur-2xl -inset-5 absolute h-96 w-96 animate-pulse left-1/2 -ml-48"
      ></div>
      <div class="relative flex flex-col items-center">
        <Ghost />
        <div class="text-center mt-5">
          <h1 class="text-6xl">#FUDFRIDAY</h1>
          <h2 class="text-4xl text-yellow-100">#WAGBOO</h2>
        </div>
      </div>
    </div>
  </main>
</template>

<style>
body {
  font-family: "Rubik", sans-serif;
}
</style>
