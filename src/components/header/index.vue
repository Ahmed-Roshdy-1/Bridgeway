<script setup lang="ts">
import BaseButton from '@/components/buttons/BaseButton.vue';
</script>

<template>
    <header class="absolute inset-x-0 top-0 z-50 text-white px-0 md:px-4">
        <div class="mx-auto flex w-full max-w-7xl items-center justify-between gap-4 px-4 py-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row  md:items-center gap-2 md:gap-16 w-full">
                <a href="#" class="shrink-0 text-xl font-bold tracking-tight" aria-label="Bridgeway home">
                    Bridgeway
                </a>

                <nav class="block" aria-label="Main navigation">
                    <ul class="flex items-center gap-2 md:gap-8">
                        <li>
                            <a href="#benefits"
                                class="text-sm md:text-base transition-colors hover:text-bridgeway-lime focus-visible:text-bridgeway-lime">Benefits</a>
                        </li>
                        <li>
                            <a href="#contact"
                                class="text-sm md:text-base transition-colors hover:text-bridgeway-lime focus-visible:text-bridgeway-lime">
                                Contact Us
                            </a>
                        </li>
                    </ul>
                </nav>
            </div>
            <BaseButton href="#contact">Get Started</BaseButton>

        </div>

    </header>
</template>
