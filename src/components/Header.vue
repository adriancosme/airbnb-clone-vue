<script setup lang="ts">
import SearchSVG from '@components/SeachSVG.vue'
import FilterSVG from '@components/FilterSVG.vue'
</script>
<template>
    <header>
        <div class="bg-white relative z-[1]">
            <div class="px-6 pt-3.5">
                <div class="flex min-w-[285px] items-stretch min-h-[56px] text-[#222222] bg-white border-x-[0.5px] border-y-[0.5px] border-solid border-[rgba(0,0,0,0.08)] rounded-[1000px] shadow-md">
                    <div class="flex min-w-[100px] w-full items-center">
                        <button class="cursor-pointer relative border-black touch-manipulation rounded-none border-solid outline-none transition-none bg-transparent flex w-full h-full items-center min-w-0 select-none p-0 m-0">
                            <div class="pl-5 pr-4 py-0">
                                <SearchSVG />
                            </div>
                            <div class="flex flex-col min-w-0 w-full pl-1">
                                <div class="flex w-full min-w-0">
                                    <span class="text-sm font-[600]">Cualquier lugar</span>
                                </div>
                                <div class="flex w-full min-w-[50px] leading-5">
                                    <div class="flex">
                                        <span class="text-xs font-normal text-[#717171]">Cualquier semana</span>
                                    </div>
                                    <div class="flex px-[5px] py-0 leading-4 text-xs">•</div>
                                    <div class="flex"><span class="text-xs font-normal text-[#717171]">¿Cuántos?</span>
                                    </div>
                                </div>
                            </div>
                        </button>
                    </div>
                    <div class="flex items-center">
                        <button type="button" class="flex select-none min-w-0 w-full h-full p-0 m-0 bg-transparent outline-none rounded-none cursor-pointer relative items-center">
                            <div
                                class="flex mx-2.5 justify-center items-center box-border w-9 h-9 border-[1px] border-solid rounded-[25px]">
                                <div class="flex items-center justify-center relative">
                                    <FilterSVG />
                                </div>
                            </div>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>