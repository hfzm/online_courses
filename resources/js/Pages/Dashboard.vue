<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';
import Welcome from '@/Components/Welcome.vue';
</script>

<template>
    <AppLayout title="Dashboard">
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Dashboard
            </h2>
        </template>

        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="p-6 bg-white overflow-hidden shadow-xl sm:rounded-lg">
                    <h1>Online Courses Platform</h1>

                    <h1 class="mt-8 text-2xl font-medium text-gray-900">Welcome to online courses platform.</h1>

                    <p class="mt-8 text-gray-500 leading-relaxed">
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Architecto culpa fuga eveniet atque aliquid ad perspiciatis nesciunt temporibus vero, assumenda dolores eos id quisquam nam nulla? Dolores debitis sequi consequuntur.
                    </p>
                </div>
            </div>
        </div>
    </AppLayout>
</template>
