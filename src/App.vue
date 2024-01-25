<script setup lang="ts">
import SideBar from './components/SideBar.vue';
import MainHeader from './components/MainHeader.vue';

</script>

<template>
    <nav class="fixed w-full">
        <MainHeader />
    </nav>
    
    <div class="grid grid-cols-6 h-screen pt-12">
        <div class="col-span-1">
            <SideBar />
        </div>
        <div class="bg-blue-400 col-span-5 p-3">
            Content
        </div>
    </div>
</template>

<style scoped>

</style>
