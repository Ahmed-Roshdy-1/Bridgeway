<script setup lang="ts">
import BaseButton from '@/components/buttons/BaseButton.vue';
import ctaImg from '@/assets/images/contact-image.webp'
</script>

<template>
    <section id="contact" class="relative my-16 scroll-mt-8 lg:my-28 lg:min-h-100 mx-2 md:mx-0 ">
        <!-- Lime arch, desktop only -->



        <div class="relative flex items-center gap-6  mb-8 ">
            <img :src="ctaImg" alt="Customer paying by card at a card reader"
                class="h-56 w-full rounded-3xl object-cover sm:h-72 lg:h-75 lg:w-1/2" />
            <svg width="598" height="308" viewBox="0 0 598 518" class="hidden lg:block" fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M594.855 517.01H170.195H1.41198C0.474278 517.042 0 517.01 0 517.01H1.41198C11.2095 516.68 71.5985 509.44 170.195 387.011C170.195 387.011 205.667 361.068 247.5 280.511C321.5 138.011 324.5 108.511 371.908 45.2969C419.226 -17.7959 486.201 1.21423 510.773 8.18875L510.914 8.22871C535.37 15.17 588.308 58.544 594.855 171.011C601.403 283.477 594.855 517.01 594.855 517.01Z"
                    fill="#EEF36A" />
            </svg>
        </div>

        <div v-reveal
            class="-mt-4 rounded-3xl bg-bridgeway-purple p-7 sm:p-8 static lg:absolute lg:bottom-0 lg:left-[32%] lg:mt-0 lg:w-115">
            <h2 class="text-3xl font-extrabold leading-tight tracking-tight text-bridgeway-lime lg:text-2xl">
                <span class="text-white lg:block">Ready to cross over to</span> better payments?
            </h2>
            <p class="mt-3 text-sm text-white/70">Get set up in minutes. No hidden fees, no long contracts.</p>
            <BaseButton class="mt-5">Get Started</BaseButton>
        </div>
    </section>
</template>