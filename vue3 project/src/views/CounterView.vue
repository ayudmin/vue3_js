<script setup>

import {useCounterStore} from "@/stores/CounterStore";

let counter = useCounterStore();

</script>

<template>

    <div>
        <h1>{{ counter.count }}</h1>

        <button 
            @click="counter.increment()"
            :disabled="! counter.remaining"
            >Increament ({{ counter.remaining}} Remaining)</button>
    </div>

</template>