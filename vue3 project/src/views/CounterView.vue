<script setup>

import {useCounterStore} from "@/stores/CounterStore";

let counter = useCounterStore();

</script>

<template>

    <div>
        <h1>{{ counter.count }}</h1>

        <button @click="counter.increment()">Increament</button>
    </div>

</template>