<script setup lang="ts">
import DefaultLayout from '@/layouts/DefaultLayout.vue';
import AppHome from '@/components/home/index.vue';
import AppBenefits from '@/components/Benefits/index.vue';
import AppContact from '@/components/contact/index.vue';
</script>

<template>
  <DefaultLayout>
    <AppHome />
    <AppBenefits />
    <AppContact />
  </DefaultLayout>
</template>
