<script setup>
import TheWelcome from "@/components/TheWelcome.vue";

    
let message = $ref("Hello world");

setTimeout(() => {
  message = "I have been changed";
},2000);

</script>

<template>
  <main>
    <TheWelcome />
    <p>{{ message }}</p>
    <input type="text" v-model="message" />
  </main>
</template>
