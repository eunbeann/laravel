<template>
    <Link href="/">Main Page</Link>&nbsp;
    <Link href="/hello">Show Page</Link>
    <div>the page with time {{ timer }}</div>
    <slot> Default </slot>
</template>

<!-- logic section -->
<script setup>
import { Link } from '@inertiajs/vue3'
import { ref } from 'vue'

const timer = ref(0)
// timer
setInterval(() => timer.value++, 1000)
</script>
