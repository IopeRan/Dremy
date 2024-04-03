<template>
    <section id="pages" class="bg-slate-200 w-full min-h-screen p-8">
        <div class="flex flex-col gap-4 text-center">
            <h5 class="text-2xl capitalize font-medium">recent property for rent</h5>
            <p class="text-sm">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor, quaerat.</p>
        </div>
        <div class="w-full grid grid-cols-1 gap-8 mt-8 lg:grid-cols-3">
            <div class="bg-white w-full h-max rounded-lg overflow-hidden shadow-sm p-4" v-for="property in properties" :key="property.id">
                <div>
                    <img :src="property.image" alt="" class="w-full h-44 object-cover rounded-lg">
                </div>
                <div class="flex flex-row items-center justify-between mt-4 capitalize">
                    <small class="text-slate-500">{{ property.status }}</small> 
                    <p class="font-medium">${{ property.price }}</p>
                </div>
                <div class="flex flex-col">
                    <span class="font-medium capitalize">{{ property.name }}</span>
                    <div class="flex flex-row mt-3">
                        <ul class="w-full flex flex-row justify-between capitalize text-slate-500">
                            <li class="flex gap-1 items-center">
                                <i class="fa-solid fa-bed w-8 h-8 grid place-content-center bg-slate-200 rounded-full"></i> {{ property.bed }} beds
                            </li>
                            <li class="flex gap-1 items-center">
                                <i class="fa-solid fa-bath w-8 h-8 grid place-content-center bg-slate-200 rounded-full"></i> {{ property.bath }} bath
                            </li>
                            <li class="flex gap-1 items-center">
                                <i class="fa-solid fa-landmark w-8 h-8 grid place-content-center bg-slate-200 rounded-full"></i> {{ property.soft }} soft
                            </li>
                        </ul>
                    </div>
                    <div class="flex flex-row items-center justify-between mt-6">
                        <small class="text-slate-500 capitalize">
                            <i class="fa-solid fa-location-dot"></i> {{ property.location }}
                        </small>
                        <a href="" class="bg-blue-900 text-white px-6 py-2 rounded-lg hover:bg-blue-800 hover:duration-150">View</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>

const properties = [
    {
        id: 1,
        image: '../../public/property/1.jpg',
        status: 'rent',
        price: '1,200',
        name: 'mitchel park plaza apartments',
        bed: 2,
        bath: 2,
        soft: 1200,
        location: 'dubai, production city'
    },
    {
        id: 2,
        image: '../../public/property/2.webp',
        status: 'rent',
        price: '1,400',
        name: 'cottonwork wood apartments',
        bed: 3,
        bath: 2,
        soft: 1000,
        location: 'dubai, dubai south world central'
    },
    {
        id: 3,
        image: '../../public/property/3.jpg',
        status: 'rent',
        price: '1,500',
        name: 'ridge st jonseph apartments',
        bed: 3,
        bath: 3,
        soft: 1800,
        location: 'washington, main downtown'
    }
]

</script>