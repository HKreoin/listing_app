<script setup></script>

<template>
    <div>
        <header class="bg-blue-800 text-white">
            <nav
                class="p-6 mx-auto max-w-screen-lg flex items-center justify-between"
            >
                <div class="space-x-6">
                    <Link :href="route('home')">Home</Link>
                </div>
            </nav>
        </header>

        <main class="p-6 mx-auto max-w-screen-lg">
            <slot />
        </main>
    </div>
</template>
