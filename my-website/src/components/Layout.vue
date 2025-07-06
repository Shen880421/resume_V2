<template>
    <div class="w-full h-dvh flex relative ltr">
        <div
            class="w-1/6 bg-gradient-to-b from-slate-600 to-slate-800 text-cyan-50 h-dvh fixed"
        >
            <LeftNav />
        </div>
        <div class="w-5/6 h-dvh absolute inset-y-0 right-0">
            <RightMain />
        </div>
    </div>
</template>
<script setup>
import LeftNav from "./LeftNav.vue";
import RightMain from "./RightMain.vue";
</script>
<style scoped></style>
