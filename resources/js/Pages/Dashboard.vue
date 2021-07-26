<template>
    <app-layout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Dashboard
            </h2>
        </template>

        <div class="py-12">
            <div class="grid grid-cols-2 gap-4">
                <div class="w-1/3">
                    <p class="text-center border-r-2 border-red-600">Hello world</p>
                </div>
                <div>
                    <p>Hello gang</p>
                </div>
            </div>
        </div>
    </app-layout>
</template>

<script>
    import AppLayout from '@/Layouts/AppLayout'

    export default {
        components: {
            AppLayout,
        },
    }
</script>
