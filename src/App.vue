<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from "../src/components/TheWelcome.vue";

</script>

<template>
  <header>
    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <RouterView />
</template>
