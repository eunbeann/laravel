<template>
    <h1>Index Page</h1>
    <Link href="/hello">Show Page</Link>
    <div>The message is {{ message }}</div>
</template>

<!-- logic section -->
<script setup>
import { Link } from '@inertiajs/vue3'
defineProps({ message: String })
</script>
