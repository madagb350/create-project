<script setup>
import { Link } from "@inertiajs/vue3";
</script>

<template>
    Inertiaテストです。<br />
    <a href="/">aタグ経由です </a><br />
    <Link href="/">Linkタグ経由です</Link><br />
    <Link :href="route('inertia.index')">名前付きルート</Link>
</template>
