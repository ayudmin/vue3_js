<script setup >

import {useCounterStore} from "@/stores/CounterStore";

let counter = useCounterStore();

</script>



<template>
    <div class="contact">
      <h1>This is a contact page</h1>
      <p>The current count is {{ counter.count }}</p>

    </div>
</template>
  