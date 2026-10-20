<script setup lang="ts">
const paths = {
    card: 'M3 6h18v12H3zM3 10h18M6 15h4',
    sync: 'M20 11a8 8 0 0 0-14-4M4 4v4h4M4 13a8 8 0 0 0 14 4m2 3v-4h-4',
    payout: 'M3 17h4l5 2 8-3a2 2 0 0 0-2-3l-5 1M8 9a3 3 0 1 0 6 0 3 3 0 0 0-6 0',
    shield: 'M12 3l7 3v5c0 5-3 8-7 10-4-2-7-5-7-10V6zM9 12l2 2 4-4',
    chart: 'M12 3a9 9 0 1 0 9 9h-9zM15 3a6 6 0 0 1 6 6h-6z',
    code: 'M8 8l-4 4 4 4M16 8l4 4-4 4M13 6l-2 12'
}

defineProps<{ name: keyof typeof paths }>()
</script>

<template>
    <svg class="h-6 w-6" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"
        stroke-linejoin="round" aria-hidden="true">
        <path :d="paths[name]" />
    </svg>
</template>
