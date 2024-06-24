<template>
    <div class="min-h-screen py-40" style="background-image: linear-gradient(115deg, #1B2A35, #6D6E6C);">
        <div class="container mx-auto">
            <div class="w-8/12 bg-white rounded-xl mx-auto shadow-lg overflow-hidden flex">
                <div class="welcome text-white w-1/2 flex flex-col items-center justify-center p-12 bg-no-repeat bg-cover bg-center">
                    <h1 class="text-3xl mb-3">Welcome to <span class="font-bold">GoRBX</span></h1>
                    <div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates enim accusantium ea ipsam fugiat labore optio quos molestiae, maxime iste impedit vel. Similique, totam iure?</p>
                    </div>
                </div>
                <div class="w-1/2 py-16 px-12">
                    <h2 class="text-3xl mb-4">Register</h2>
                    <p class="mb-4">Create your account. It's free and only take a minute!</p>
                    <form action="">
                        <div class="space-y-5">
                            <input class="border border-gray-400 py-1 px-2 rounded-lg w-full" type="text" placeholder="Username">
                            <input class="border border-gray-400 py-1 px-2 rounded-lg w-full" type="email" placeholder="Email">
                            <input class="border border-gray-400 py-1 px-2 rounded-lg w-full" type="password" placeholder="Password">
                            <input class="border border-gray-400 py-1 px-2 rounded-lg w-full" type="password" placeholder="Confirm Password">
                        </div>
                        <div class="mt-5">
                            <input type="checkbox" class="border border-gray-400">
                            <span>
                                I accept the <a href="#" class="text-blue-600 font-semibold">Terms of use</a> & <a href="#" class="text-blue-600 font-semibold">Privacy Policy</a>
                            </span>
                        </div>
                        <div class="mt-5">
                            <button class="w-full bg-blue-500 py-3 text-center text-white">Register</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scope>
    .welcome{
        background-image: url("~/assets/images/main-page.png");
    }
</style>