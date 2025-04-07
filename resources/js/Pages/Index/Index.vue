<template>
    <MainLayout>
        <h1>Index Page</h1>
        <Link href="/hello">Show Page</Link>
        <div>The message is {{ message }}</div>
    </MainLayout>
</template>

<!-- logic section -->
<script setup>
import { Link } from '@inertiajs/vue3'
import MainLayout from '../../Layouts/MainLayout.vue'
defineProps({ message: String })
</script>
