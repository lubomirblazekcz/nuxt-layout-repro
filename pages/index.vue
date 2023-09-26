<script setup>
    import { definePageMeta } from '#imports'

    definePageMeta({
        layout: 'login'
    })
</script>

<template>
    <NuxtLayout>
        <div class="page-login">
            <NuxtLink to="/page-1">Login</NuxtLink>
        </div>
    </NuxtLayout>
</template>
