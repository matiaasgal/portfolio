<script>
export default {
    data() {
        return {
            title: 'Estudios',
        };
    },
}
</script>

<template>
    <main class="mt-10">
        <div class="title flex gap-3">
            <h2 class="text-black font-bold text-4xl mb-6 mt-1">{{ title }}</h2>
            <img src="../assets/student.svg" alt="" class="w-10 h-12">
        </div>
        <h3 class="text-black font-semibold text-medium nombre">Universidad de Santiago de Chile</h3>
        <div class="info flex justify-between mb-3">
            <h4 class="text-gray-600 font-semibold mx-2">Analista en <span class="text-violet-700 font-semibold">Computacion Cientifica</span></h4>
            <h4 class="text-gray-600 font-semibold">2025</h4>
        </div>
        <hr class="mb-3">
        <h3 class="text-black font-semibold text-medium nombre">Talento Digital para Chile</h3>
        <div class="info flex justify-between">
            <h4 class="text-gray-600 font-semibold mx-2">Bootcamp <span class="text-violet-700 font-semibold">Desarrollo de Aplicaciones Web</span> con VueJS</h4>
            <h4 class="text-gray-600 font-semibold">2024</h4>
        </div>
    </main>
</template>

<style scoped>
.nombre {
    @media (max-width: 581px) {
        text-align: center;
    }
}
.info {
    @media (max-width: 581px) {
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }
}
.info > h4{
    @media (max-width: 581px) {
        text-align: center;
    }
}
.title {
    @media (max-width: 581px) {
        justify-content: center;
    }
}
</style>