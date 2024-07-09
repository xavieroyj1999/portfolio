<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
    <div class="flex flex-col h-screen">
        <nav class="flex justify-between px-3 py-2">
            <div class="flex gap-x-4">
                <RouterLink to="/">Home</RouterLink>
                <RouterLink to="/about">About</RouterLink>
                <RouterLink to="/contact">Contact</RouterLink>
                <RouterLink to="/blog">Blog</RouterLink>
            </div>

            <div>
                <button>Enable Dark Mode</button>
            </div>
        </nav>

        <div class="grow">
            <RouterView />
        </div>
    </div>
</template>
