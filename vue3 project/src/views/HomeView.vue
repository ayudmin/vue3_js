<script>
import flash from "@/mixins/flash.js"

export default {
  mixins: [flash]
};

</script>

<template>
  <main>
    <p>
      <button @click="flash('It works')">Click me</button>
    </p>
  </main>
</template>
