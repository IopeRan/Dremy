<template>
    <section id="feature" class="bg-white w-full min-h-screen p-8">
        <h2 class="text-2xl font-medium px-12">Featured Property</h2>
        <div class="w-full flex flex-col gap-4 lg:flex-row mt-10 lg:px-12">
            <div class="flex flex-col gap-4 lg:w-1/2 lg:h-full">
                <div style="background-image: url('feature/1.avif');" class="w-full h-64 lg:w-full lg:h-96 bg-cover bg-center rounded-lg shadow-md px-4 py-3 flex items-end">
                    <div class="bg-white w-full h-max py-1 px-3 rounded-lg flex flex-row justify-between shadow-md items-center">
                        <div class="flex flex-col">
                            <p class="font-medium">Paradise Residence</p>
                            <small class="text-slate-500"><i class="fa-solid fa-location-dot"></i> Laweyan, Surakarta</small>
                        </div>
                        <div>
                            <button class="text-xs bg-slate-200 w-8 h-8 rounded-full">
                                <i class="fa-solid fa-heart"></i>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="flex flex-col gap-4 lg:w-1/2">
                <div style="background-image: url('feature/2.webp');" class="w-full h-36 lg:h-1/2 bg-cover bg-center rounded-lg shadow-md px-4 py-3 flex items-end">
                    <div class="bg-white w-full h-max py-1 px-3 rounded-lg flex flex-row justify-between shadow-md items-center">
                        <div class="flex flex-col">
                            <p class="font-medium">Cluster Nirwana</p>
                            <small class="text-slate-500"><i class="fa-solid fa-location-dot"></i> Dubai, Production City</small>
                        </div>
                        <div>
                            <button class="text-xs bg-slate-200 w-8 h-8 rounded-full">
                                <i class="fa-solid fa-heart"></i>
                            </button>
                        </div>
                    </div>
                </div>
                <div style="background-image: url('feature/3.jpg');" class="w-full h-36 lg:h-1/2 bg-cover bg-center rounded-lg shadow-md px-4 py-3 flex items-end">
                    <div class="bg-white w-full h-max py-1 px-3 rounded-lg flex flex-row justify-between shadow-md items-center">
                        <div class="flex flex-col">
                            <p class="font-medium">Srikandi Housing</p>
                            <small class="text-slate-500"><i class="fa-solid fa-location-dot"></i> New York, Fortune 2</small>
                        </div>
                        <div>
                            <button class="text-xs bg-slate-200 w-8 h-8 rounded-full">
                                <i class="fa-solid fa-heart"></i>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>