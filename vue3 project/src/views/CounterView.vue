<script setup>

import {counter} from "@/stores/counterStore";

</script>

<template>

    <div>
        <h1>{{ counter.count }}</h1>

        <button @click="counter.increment()">Increament</button>
    </div>

</template>