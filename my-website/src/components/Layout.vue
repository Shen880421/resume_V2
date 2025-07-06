<template>
    <div class="w-full h-dvh flex relative">
        <div
            class="w-1/6 bg-gradient-to-b from-slate-600 to-slate-800 text-cyan-50 sticky h-dvh"
        >
            <LeftNav />
        </div>
        <div class="w-5/6 h-dvh">
            <RightMain />
        </div>
    </div>
</template>
<script setup>
import LeftNav from "./LeftNav.vue";
import RightMain from "./RightMain.vue";
</script>
<style scoped></style>
