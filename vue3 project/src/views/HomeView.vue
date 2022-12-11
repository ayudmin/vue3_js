<script setup>

  import { ref, watch } from 'vue';

  import { useStorage } from "@/composables/useStorage";

  let food = useStorage('food');

  let age = useStorage('age', 10);


</script>

<template>

  <main>

    <p>
      What is your favorite food? <input type="text" v-model="food" />
    </p>

    <p>
      How old are you? <input type="text" v-model="age" />
    </p>

  </main>
</template>