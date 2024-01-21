<script setup lang="ts">
import SideBar from './components/SideBar.vue';

</script>

<template>
    <nav class="p-3 fixed bg-red-400 w-full">
        Header
    </nav>
    
    <div class="grid grid-cols-6 h-screen pt-12">
        <div class="bg-orange-400 col-span-1 p-3">
            <SideBar/>
        </div>
        <div class="bg-blue-400 col-span-5 p-3">
            Content
        </div>
    </div>
</template>

<style scoped>

</style>
