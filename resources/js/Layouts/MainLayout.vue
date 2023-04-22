<template>
    <Link href="/">Main Page</Link>&nbsp;
    <Link href="/hello">Show Page</Link>
    <slot>default</slot>
</template>

<script setup>
    import {Link} from '@inertiajs/inertia-vue3'
</script>