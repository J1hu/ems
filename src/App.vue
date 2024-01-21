<script setup lang="ts">
import SideBar from './components/SideBar.vue';

</script>

<template>
    <!-- HEADER -->
    <div class="p-3">Header</div>
    
    <!-- MAIN CONTENT -->
    <div class="grid grid-cols-5 h-screen">
        <!-- SIDEBAR -->
        <div class="bg-orange-400 col-span-1 p-3">
            <SideBar/>
        </div>
        <!-- CONTENT -->
        <div class="bg-blue-400 col-span-4 p-3">
            Content
        </div>
    </div>
</template>

<style scoped>

</style>
