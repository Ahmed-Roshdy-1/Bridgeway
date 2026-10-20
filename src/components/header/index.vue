<script setup lang="ts">
</script>

<template>
    <header class="fixed inset-x-0 top-0 z-50 text-white px-0 md:px-4">
        <div class="mx-auto flex w-full max-w-7xl items-center justify-between gap-4 px-4 py-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row  md:items-center gap-2 md:gap-16 w-full">
                <a href="#" class="shrink-0 text-xl font-bold tracking-tight" aria-label="Bridgeway home">
                    Bridgeway
                </a>

                <nav class="block" aria-label="Main navigation">
                    <ul class="flex items-center gap-2 md:gap-8">
                        <li>
                            <a href="#"
                                class="text-sm md:text-base transition-colors hover:text-bridgeway-lime focus-visible:text-bridgeway-lime">Benefits</a>
                        </li>
                        <li>
                            <a href="#"
                                class="text-sm md:text-base transition-colors hover:text-bridgeway-lime focus-visible:text-bridgeway-lime">
                                Contact Us
                            </a>
                        </li>
                    </ul>
                </nav>
            </div>

            <button type="button"
                class="min-h-11 text-sm min-w-32 md:min-w-40 items-center justify-center gap-3 rounded-full bg-bridgeway-lime px-2 font-semibold text-black transition-colors cursor-pointer hover:text-white hover:bg-bridgeway-green hover:text-bridgeway-purple focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-bridgeway-lime md:flex">
                Get Started <span aria-hidden="true">→</span>
            </button>

        </div>

    </header>
</template>
