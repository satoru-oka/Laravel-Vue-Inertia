<template>
    <MainLayout>
        <div>Show</div>
        <Link href="/">MainPage</Link>
    </MainLayout>
</template>

<script setup>
    import {Link} from '@inertiajs/inertia-vue3'
</script>

<script>
    import MainLayout from '../../Layouts/MainLayout.vue'
    export default {
        layout: MainLayout
    }
</script>