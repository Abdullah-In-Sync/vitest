<template>
    <div>
        {{ count }}
    </div>
    <button @click="handleIncrement">Increase</button>
    <button @click="handleDecrement">Decrease</button>
</template>
<script setup>
const count = ref(0)
function handleIncrement() {
count++;
}
function handleDecrement() {
    count--;
}
</script>