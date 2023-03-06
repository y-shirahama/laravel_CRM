<script setup>
import { Link } from '@inertiajs/vue3';
</script>

<template xmlns="http://www.w3.org/1999/html">
    <p>Inertiaテストです。</p>
    <a href="/">aタグ経由です。</a><br/>
    <Link href="/">Link経由です。</Link>
    <Link :href="route('inertia.index')">名前付きルートの確認です。</Link>
</template>

<style scoped>

</style>
