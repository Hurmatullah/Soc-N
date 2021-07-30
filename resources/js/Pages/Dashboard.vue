<template>
    <app-layout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Dashboard
            </h2>
        </template>
        <div class="mt-2">
            <div class='w-screen h-screen flex'>
                <div class="w-3/12 p-2 bg-white h-full">
                    <div class="bg-blue-100 w-full h-24 border-r-8 border-red-600 mt-3">
                        <img :src="$page.props.user.profile_photo_url" class="rounded-full w-16 h-16 object-cover ml-3 inline" alt="" srcset="">
                        <span class="ml-3">{{$page.props.user.name}}</span>
                    </div>
                </div>
                <div class="w-9/12 p-2 space-y-2 overflow-y-scroll">
                    <div class="bg-blue-100 w-full h-24 border"></div>
                    <div class="bg-blue-100 w-full h-24 border"></div>
                    <div class="bg-blue-100 w-full h-24 border"></div>
                    <div class="bg-blue-100 w-full h-24 border"></div>
                    <div class="bg-blue-100 w-full h-24 border"></div>
                    <div class="bg-blue-100 w-full h-24 border"></div>
                    <div class="bg-blue-100 w-full h-24 border"></div>
                    <div class="bg-blue-100 w-full h-24 border"></div>
                    <div class="bg-blue-100 w-full h-24 border"></div>
                    <div class="bg-blue-100 w-full h-24 border"></div>
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
