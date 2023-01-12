<template>
    <header
        class="border-b flex flex-col-reverse bg-gray-50/10 w-full py-2 px-4 top-0 z-1 gap-4 items-center sticky backdrop-blur-md md:flex-row md:py-6 md:gap-0 md:justify-between 2xl:px-12 ">
        <nav class="flex gap-4">
            <NuxtLink class="font-normal text-lg text-gray-800/60 hover:text-gray-800" to="/">
                Home
            </NuxtLink>
            <NuxtLink class="font-normal text-lg text-gray-800/60 hover:text-gray-800" to="/about">
                About
            </NuxtLink>
        </nav>
        <img src="../public/logo2.svg" class="h-20" alt="logo">
        <div class="flex gap-4">
            <NuxtLink class="font-normal text-lg text-gray-800/60 hover:text-gray-800" to="/">
                works
            </NuxtLink>
            <NuxtLink class="font-normal text-lg text-gray-800/60 hover:text-gray-800" to="/">
                services
            </NuxtLink>
        </div>
    </header>
</template>
