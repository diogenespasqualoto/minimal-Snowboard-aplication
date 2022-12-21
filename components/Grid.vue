<template>
    <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-3 px-4 gap-8 2xl:px-0">
        <template v-for="n in 8">
            <div class="group w-full">
                <img :src="`../img/Archivo_${n}.jpeg`"
                    class="rounded-lg cursor-pointer object-cover h-ful w-full transform-gpu transition-all duration-300 ese-in-out will-change-transform group-hover:scale-110 group-hover:group-odd:rotate-20 group-hover:group-even:-rotate-10"
                    alt="" width="w-full" height="480">
                <div class="flex flex-col py-2 ">
                    <span class="text-lg text-gray-800 inline">
                        Archivo {{ n }}
                    </span>
                    <p class="text-base w-full text-gray-800/60 inline">
                        place of Archivo {{ n }}
                    </p>
                </div>
            </div>
        </template>
    </div>
</template>
