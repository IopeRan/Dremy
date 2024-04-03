<script setup>
    import NavbarComponent from './NavbarComponent.vue'
</script>
<template>
    <section id="home" class="bg-[url('home-bg.jpg')] w-full min-h-screen bg-cover bg-center">
        <div class="bg-slate-900 w-full h-screen bg-opacity-40">
            <NavbarComponent></NavbarComponent>
            <main class="w-full h-max mt-32 flex flex-col justify-center items-center">
                <div class="flex flex-col gap-4">
                    <h5 class="px-8 text-white text-center font-light text-3xl lg:text-4xl">
                        We'll Build
                        <span class="font-medium">House of Your Dream</span>
                    </h5>
                    <p class="text-center text-slate-200 px-6 font-light lg:text-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, assumenda!</p>
                    <div class="px-6 lg:px-0">
                        <div class="bg-white w-full px-4 py-3 rounded-lg flex flex-row">
                            <form action="" class="w-full flex justify-between">
                                <input type="text" class="outline-none w-full" placeholder="Search">
                                <button type="submit" class="bg-blue-900 text-white px-4 py-2 rounded-lg hover:bg-blue-800 hover:duration-150">Search</button>
                            </form>
                        </div>
                    </div>
                </div>
            </main>
        </div>
    </section>
</template>