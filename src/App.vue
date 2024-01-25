<script setup lang="ts">
import SideBar from './components/SideBar.vue';
import MainHeader from './components/MainHeader.vue';
import MainContent from './components/MainContent.vue';

</script>

<template>
    <nav class="fixed w-full z-20">
        <MainHeader />
    </nav>
    
    <div class="grid grid-cols-6 h-screen pt-12">
        <div class="col-span-1 z-10">
            <SideBar />
        </div>
        <div class="col-span-5 z-0">
            <MainContent />
        </div>
    </div>
</template>

<style scoped>

</style>