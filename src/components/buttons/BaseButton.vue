<script setup lang="ts">
</script>

<template>
    <button type="button"
        class="min-h-11 text-sm min-w-32 md:min-w-40 items-center justify-center gap-3 rounded-full bg-bridgeway-lime px-2 font-semibold text-black transition-colors cursor-pointer hover:text-white hover:bg-bridgeway-green hover:text-bridgeway-purple focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-bridgeway-lime md:flex">
        <slot>Get Started</slot>
        <span aria-hidden="true">→</span>
    </button>
</template>