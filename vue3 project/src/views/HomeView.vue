<script setup>
import TabableTextarea from '@/components/TabableTextarea.vue';
import { ref } from 'vue';

    let comment = ref('test value');

    setTimeout(() =>{
      comment.value = 'it works!';
    }, 2000)

</script>

<template>

  <main>
    <form >
        <TabableTextarea v-model="comment"  style="width: 100%; height: 300px;"></TabableTextarea>
    </form>
  </main>
</template>