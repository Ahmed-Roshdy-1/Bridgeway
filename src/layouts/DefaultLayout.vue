<script setup lang="ts">
import AppHeader from '@/components/header/index.vue';
import AppFooter from '@/components/footer/index.vue';


</script>

<template>
    <div class="mx-auto flex min-h-screen w-full max-w-7xl flex-col px-0 md:px-4 sm:px-6 lg:px-8">
        <AppHeader />

        <main class="relative">
            <slot />
        </main>

        <AppFooter />
    </div>
</template>