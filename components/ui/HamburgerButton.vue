<template>
    <button class="relative group" @click="toggleHamburgerButton">
        <div :class="[active ? 'ring-4' : '']"
            class="relative flex items-center justify-center rounded-full w-[50px] h-[50px] transform transition-all bg-slate-700 ring-0 ring-gray-300 hover:ring-8 ring-opacity-30 duration-200 shadow-md">
            <div :class="[active ? '-rotate-[45deg]' : '']"
                class="flex flex-col justify-between w-[20px] h-[20px] transform transition-all duration-300 origin-center">
                <div :class="[active ? '-rotate-90 h-[1px] translate-y-[1px]' : '']"
                    class="bg-white h-[2px] w-1/2 rounded transform transition-all duration-300 origin-right delay-75">
                </div>
                <div class="bg-white h-[1px] rounded"></div>
                <div :class="[active ? '-rotate-90 h-[1px] translate-y-[1px]' : '']"
                    class="bg-white h-[2px] w-1/2 rounded self-end transform transition-all duration-300 origin-left delay-75">
                </div>
            </div>
        </div>
    </button>
</template>

<script setup>
import { computed, ref } from 'vue';

const props = defineProps(['modelValue'])
const emit = defineEmits(['update:modelValue'])

const active = computed(() => props.modelValue)

const toggleHamburgerButton = () => (emit('update:modelValue', !props.modelValue));

</script>