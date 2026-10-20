<script setup lang="ts">
import FeatureCard from './FeatureCard.vue'

// Single source of truth for the cards. Even index = dark card (gives the checker pattern on desktop too).
const features = [
    { icon: 'card', title: 'Accept Payments', description: 'Take cards, wallets, and bank transfers online and in person through a single integration.' },
    { icon: 'sync', title: 'Reconcile automatically', description: 'Every transaction is matched to your books in real time, so month-end stops being a chore.' },
    { icon: 'payout', title: 'Send Payouts', description: 'Pay suppliers, partners, and staff in minutes, in bulk or one at a time.' },
    { icon: 'shield', title: 'Secure by default', description: 'Built-in fraud checks, encryption, and identity verification protect every payment.' },
    { icon: 'chart', title: 'Clear reporting', description: "Live dashboards show where your money is, what's settled, and what's pending." },
    { icon: 'code', title: 'Built for developers', description: 'Clean APIs, sandbox testing, and webhooks help your team ship in days, not months.' }
] as const
</script>

<template>
    <section id="benefits" class="scroll-mt-8 py-8 lg:py-16 mx-2 md:mx-0">
        <div class="flex flex-col gap-4 lg:flex-row lg:items-start lg:justify-between lg:gap-10">
            <h2 v-reveal class="text-4xl font-extrabold leading-[1.05] tracking-tight lg:max-w-155 lg:text-5xl">
                Everything payments, <br />on one bridge
            </h2>
            <p v-reveal="100" class="max-w-110 text-lg leading-snug lg:text-xl">
                One platform connects you to customers, banks, and your own books, so money moves without the
                friction.
            </p>
        </div>

        <div class="mt-8 grid gap-4 md:grid-cols-2 lg:mt-14 lg:grid-cols-3 lg:gap-5">
            <FeatureCard v-for="(f, i) in features" :key="f.title" v-bind="f" :dark="i % 2 === 0"
                v-reveal="(i % 3) * 100" />
        </div>
    </section>
</template>
