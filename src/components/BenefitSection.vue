<script setup lang="ts">
import plantIcon from '../assets/plant-icon.svg'
import lockIcon from '../assets/lock-icon.svg'
import stickIcon from '../assets/stick-icon.svg'
import chainIcon from '../assets/chain-icon.svg'
import chieldIcon from '../assets/chield-icon.svg'
import medalIcon from '../assets/medal-icon.svg'
const benefits = [
    {
        img: plantIcon,
        title: "Ideal for Beginner Clients",
        description: "Increase trading volumes as new traders gain comfort by following successful traders in forex markets and beyond into stocks, options, commodities, and more…"
    },
    {
        img: lockIcon,
        title: "Low Barriers to Entry",
        description: "CommuniTraders software is free and clients can start with just a $100 minimum investment."
    },
    {
        img: stickIcon,
        title: "Simple Interface",
        description: "A simple GUI provides needed features and tools but isn’t bogged down by non-core features. This allows clients to get setup quickly and start trading."
    },
    {
        img: chainIcon,
        title: "No Long-Term Commitments",
        description: "Clients can easily signup to start, change signal providers, or stop the service. There is no long-term lockup."
    },
    {
        img: chieldIcon,
        title: "Funds Safety",
        description: "CommuniTraders benefits from the same strong regulation and banking partners standalone Tradeview clients enjoy along with transparency and negative balance protection."
    },
    {
        img: medalIcon,
        title: "Tradeview Runs CommuniTrader",
        description: "You will experience the Tradeview service you know and love, no gimmicks or hidden fees, excellent live customer support, and your dedicated account manager."
    }
]
</script>

<template>
    <section class="p-10 py-16 grid grid-cols-12 gap-6">
        <div v-for="benefit in benefits"
            class="h-[260px] shadow-lg border-2 border-[#00000014] p-5 px-7 space-y-2 col-span-4">
            <img class="w-[50px] h-[50px]" :src="benefit.img">
            <h6 class="font-bold text-base text-primary">
                {{ benefit.title }}
            </h6>
            <p class="text-sm text-[#363636]">{{ benefit.description }}</p>
        </div>
    </section>
</template>