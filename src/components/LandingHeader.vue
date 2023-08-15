<script setup></script>
<template>
    <header class="z-10 fixed top-0">
        <section class="w-full h-[80px] bg-secondary grid grid-cols-12 items-center px-6">
            <div class="col-span-2">
                <img class="h-[56px]" src="../assets/logo.svg" alt="">
            </div>
            <nav class="flex col-start-4 col-span-6">
                <a class="text-white font-black tracking-[4.8px] text-xs mx-5" href="#">FOREX</a>
                <a class="text-white font-black tracking-[4.8px] text-xs mx-5" href="#">STOCKS</a>
                <a class="text-white font-black tracking-[4.8px] text-xs mx-5" href="#">FUTURES</a>
                <a class="text-white font-black tracking-[4.8px] text-xs mx-5" href="#">TradeGATEHub</a>
            </nav>
            <div class="flex col-span-3 justify-center">
                <a class="text-white tracking-[0px] font-medium text-xs flex gap-1 mx-3" href="#">
                    <span>Log&nbsp;in</span>
                    <img src="../assets/arrow-icon.svg" alt="">
                </a>
                <span class="border-e-[1px]"></span>
                <a class="text-white tracking-[0px] font-light text-xs mx-3" href="#">
                    <span>Contact Us</span>
                </a>
                <a class="text-white tracking-[0px] font-light text-xs flex gap-1 mx-3" href="#">
                    <span>English</span>
                    <img src="../assets/planet-icon.svg" alt="">
                    <img src="../assets/arrow-icon.svg" alt="">
                </a>
            </div>
        </section>
        <nav class="bg-shadow-header h-[100px] w-full grid grid-cols-12 pt-7">
            <div class="col-span-5 flex items-start">
                <a class="text-white tracking-[0px] text-sm ml-12" href="#">Markets</a>
                <a class="text-white tracking-[0px] text-sm ml-12  flex gap-1" href="#">
                    <span>Company</span>
                    <img src="../assets/arrow-icon.svg" alt="">
                </a>
                <a class="text-white tracking-[0px] text-sm ml-12" href="#">Accounts</a>
                <a class="text-white tracking-[0px] text-sm ml-12  flex gap-1" href="#">
                    <span>Platforms</span>
                    <img src="../assets/arrow-icon.svg" alt="">
                </a>
                <a class="text-white tracking-[0px] text-sm ml-10" href="#">Pricing</a>
            </div>

            <div class="col-span-7 flex items-start">
                <a class="text-white tracking-[0px] text-sm ml-2" href="#">Introducing Brokers</a>
                <a class="text-white tracking-[0px] text-sm ml-12" href="#">Education</a>
                <a class="text-white tracking-[0px] text-sm ml-12  flex gap-1" href="#">
                    <span>Support</span>
                    <img src="../assets/arrow-icon.svg" alt="">
                </a>
            </div>
        </nav>
    </header>
</template>

<style scoped>
.bg-shadow-header {
    background: transparent linear-gradient(180deg, #181F29 0%, #181F29 18%, #181F2960 59%, #181F2900 100%) 0% 0% no-repeat padding-box;
}
</style>
