<template>
    <div class="w-full h-screen flex">
        <div class="w-1/6 bg-slate-600 text-cyan-50 sticky">
            <LeftNav />
        </div>
        <div class="w-5/6">
            <RightMain />
        </div>
    </div>
</template>
<script setup>
import LeftNav from "./LeftNav.vue";
import RightMain from "./RightMain.vue";
</script>
<style scoped></style>
