<template>
    <div class="bg-gradient-to-t from-stone-400 via-stone-100 to-stone-50">
        <h1
            class="bitcount-grid-double-font tracking-wide text-center h-screen content-center max-md:text-2xl min-md:text-6xl shadow-xl/30 bg-amber-50"
        >
            Hello! <br />My name is
            <span class="text-8xl text-amber-600">Shen</span>.
        </h1>
        <main class="h-full">
            <BasicInfo />
            <Skill />
            <WorkExperience />
            <Portfolio />
            <Footerdiv />
        </main>
    </div>
</template>
<script setup>
import BasicInfo from "./BasicInfo.vue";
import Skill from "./Skill.vue";
import WorkExperience from "./WorkExperience.vue";
import Portfolio from "./Portfolio.vue";
import Footerdiv from "./Footerdiv.vue";
</script>
<style scoped></style>
