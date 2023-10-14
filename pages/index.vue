<template>
  <div>
    <Alert /> <Profile />
    <!-- <img src="~/assets/island.png" alt="" /> -->
    <img src="@/assets/island.png" alt="" />
    <IconsBell />
  </div>
</template>

<script setup lang="ts">
import { onClickOutside } from "@vueuse/core";

const { sayHello } = useUtils();
sayHello();

const { $sayHello } = useNuxtApp();
$sayHello("halo ini saya hilmi");
</script>

<style scoped></style>
