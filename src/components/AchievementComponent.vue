<template>
    <section id="listings" class="bg-slate-200 w-full h-max py-6">
        <div class="flex flex-col">
            <h3 class="text-2xl text-center font-medium">Achievement</h3>
            <p class="px-8 text-center font-light text-sm">Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt, voluptatibus.</p>
        </div>
        <div class="w-full grid grid-cols-2 gap-6 mt-8 lg:grid-cols-4 lg:px-20">
            <div v-for="achievement in achievements" :key="achievement.id" class="flex flex-col justify-center items-center text-center">
                <div>
                    <i :class="achievement.icon " class="text-4xl text-green-600"></i>
                </div>
                <div>
                    <p class="text-lg font-medium">{{ achievement.total }}+</p>
                </div>
                <div>
                    <small class="font-medium capitalize">{{ achievement.title }}</small>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>

const achievements = [
    {
        id: 1,
        icon: 'fa solid fa-rectangle-list',
        total: 2500,
        title: 'completed property'
    },
    {
        id: 2,
        icon: 'fa solid fa-universal-access',
        total: 3500,
        title: 'property sales'
    },
    {
        id: 3,
        icon: 'fa solid fa-building',
        total: 8500,
        title: 'apartment rent'
    },
    {
        id: 4,
        icon: 'fa solid fa-users',
        total: 4500,
        title: 'happy client'
    },   
]

</script>