<script setup lang="ts">

const count = useState('counter', () => 0);

</script>

<template>
    <div>
        <div>{{ count }}</div>
        <button @click="count++">Increment</button>
    </div>
</template>