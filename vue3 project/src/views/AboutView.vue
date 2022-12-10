<script>
  import flash from "@/mixins/flash.js"

  export default {
    mixins: [flash]
  }
</script>

<template>
  <div>
      <p>
          <button @click="flash('It works on the About page!')">Click</button>
      </p>
  </div>
</template>

