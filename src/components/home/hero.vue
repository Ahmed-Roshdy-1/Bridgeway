<script setup lang="ts">

</script>
<template>
    <div
        class="flex flex-col justify-between bg-bridgeway-purple rounded-b-4xl xl:bg-transparent  w-full min-h-[calc(100vh-18rem)]">
        <div class="mt-8">
            <div class="">
                <h1
                    class="z-50 static xl:absolute top-90 left-18 text-4xl px-4 font-bold text-bridgeway-lime mt-20 md:mt-32 md:text-6xl lg:text-7xl">
                    Your way to
                </h1>
                <svg width="1310" height="786" viewBox="0 0 1310 786" fill="none" xmlns="http://www.w3.org/2000/svg"
                    class="hidden xl:block absolute top-0 -left-10 z-20">
                    <path
                        d="M253.71 785C-101.79 769 20.2098 0 20.2098 0H1300.21C1300.21 0 1364 337 1150.5 400.5C936.998 464 849.21 330 670.71 419C492.21 508 609.21 801 253.71 785Z"
                        class="fill-bridgeway-purple" />
                </svg>
            </div>
            <div>
                <svg width="879" height="735" viewBox="0 0 879 735" fill="none" xmlns="http://www.w3.org/2000/svg"
                    class="hidden xl:block absolute top-0 right-0 z-10">
                    <path
                        d="M803 0H76C34.0264 0 0 34.0264 0 76V659C0 700.974 34.0264 735 76 735H650.6C692.574 735 726.6 700.774 726.6 658.8C726.6 616.826 760.826 582.6 802.8 582.6C844.774 582.6 879 548.574 879 506.6V76C879 34.0264 844.974 0 803 0Z"
                        class="fill-bridgeway-lime" />
                </svg>
                <div
                    class="flex flex-col items-start justify-center gap-4 mt-2 static xl:absolute top-120 left-138 right-0 z-50 text-bridgeway-lime xl:text-bridgeway-purple text-start px-4">
                    <h1 class="text-4xl font-bold md:text-6xl lg:text-7xl">better payments</h1>
                    <p class="text-lg md:text-2xl max-w-75 text-start text-bridgeway-gray xl:text-bridgeway-purple">
                        Accept, send,
                        and
                        reconcile
                        payments in one
                        place. </p>
                </div>
            </div>
        </div>
        <img src="@/assets/images/hero-desktop.webp" alt="Hero Image"
            class="hidden xl:block absolute top-60 -right-20 z-30" />
        <div class="flex  flex-col xs:flex-row items-center justify-between gap-4 mt-10 w-full px-4 mb-8">
            <img src="@/assets/images/hero-content.webp" alt="Hero Image" class="xl:hidden " />
            <button
                class="flex items-center gap-2 static xl:absolute -bottom-5 right-0 z-50 bg-bridgeway-purple p-8 rounded-4xl text-start">
                <svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M36.0011 2V28C36.0011 28.5304 35.7904 29.0391 35.4153 29.4142C35.0403 29.7893 34.5315 30 34.0011 30C33.4707 30 32.962 29.7893 32.5869 29.4142C32.2118 29.0391 32.0011 28.5304 32.0011 28V6.8275L3.41611 35.415C3.04083 35.7903 2.53184 36.0011 2.00111 36.0011C1.47038 36.0011 0.961393 35.7903 0.586112 35.415C0.210831 35.0397 0 34.5307 0 34C0 33.4693 0.210831 32.9603 0.586112 32.585L29.1736 4H8.00111C7.47068 4 6.96197 3.78929 6.5869 3.41421C6.21183 3.03914 6.00111 2.53043 6.00111 2C6.00111 1.46957 6.21183 0.96086 6.5869 0.585787C6.96197 0.210714 7.47068 0 8.00111 0H34.0011C34.5315 0 35.0403 0.210714 35.4153 0.585787C35.7904 0.96086 36.0011 1.46957 36.0011 2Z"
                        class="fill-bridgeway-lime" />
                </svg>

            </button>
        </div>

    </div>
</template>