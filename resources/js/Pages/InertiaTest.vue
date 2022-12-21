<script setup>
import { Link } from '@inertiajs/inertia-vue3';
</script>

<template>
inertia test<br>
<a href="/">aタグ Inertia Test</a><br>
<Link href="/">Link Inertia Test</Link><br>
<Link :href="route('inertia.index')">:href Link InertiaController index</Link>
</template>
