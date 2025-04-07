<template>
    <h1>Show page</h1>
    <Link href="/">Index Page</Link>
</template>

<!-- logic section -->
<script setup>
import { Link } from '@inertiajs/vue3'
</script>

<script>
import MainLayout from '../../Layouts/MainLayout.vue'
export default {
    layout: MainLayout
}
</script>
