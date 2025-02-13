<script setup>
import Icon from '../assets/icons/navbar-icon.svg'

const navbarData = {
    websiteName: 'RegiM',
    buttonText: 'Get Early Access'
}
</script>

<template>
    <nav class="w-full min-h-8 flex items-center justify-between px-8 py-4">
        <div class="flex justify-center items-center gap-2.5">
            <img :src="Icon" alt="">
            <h1 class="font-bold text-2xl cursor-default max-sm:text-base">{{ navbarData.websiteName }}</h1>
        </div>
        <a href="#"
            class="px-4 py-2.5 bg-[#0876DD] text-white rounded-md font-semibold hover:bg-blue-500 transition-all max-sm:py-1.5 max-sm:px-3 max-sm:text-xs">{{
                navbarData.buttonText }}</a>
    </nav>
</template>