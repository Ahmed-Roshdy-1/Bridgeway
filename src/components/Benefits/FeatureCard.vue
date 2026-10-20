<script setup lang="ts">
import FeatureIcon from './FeatureIcon.vue'

defineProps<{
    icon: 'card' | 'sync' | 'payout' | 'shield' | 'chart' | 'code'
    title: string
    description: string
    dark?: boolean
}>()
</script>

<template>
    <article class="group flex min-h-75 flex-col justify-between gap-12 rounded-3xl border p-7 transition duration-300
                  hover:-translate-y-1.5 hover:shadow-xl hover:shadow-bridgeway-purple/20 lg:min-h-75"
        :class="dark ? 'border-bridgeway-purple bg-bridgeway-purple text-white' : 'border-bridgeway-purple/15 bg-white text-bridgeway-purple'">
        <span
            class="flex h-12 w-12 items-center justify-center rounded-xl transition-transform duration-300 group-hover:rotate-6"
            :class="dark ? 'bg-bridgeway-lime text-bridgeway-purple' : 'bg-bridgeway-purple text-bridgeway-lime'">
            <FeatureIcon :name="icon" />
        </span>
        <div>
            <h3 class="text-lg font-semibold">{{ title }}</h3>
            <p class="mt-2 text-sm leading-relaxed" :class="dark ? 'text-white' : 'text-bridgeway-purple'">{{
                description }}
            </p>
        </div>
    </article>
</template>
