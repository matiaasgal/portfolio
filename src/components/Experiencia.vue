<script>
export default {
    data() {
        return {
            title: 'Experiencia',
        };
    },
}
</script>

<template>
    <main class="mt-10">
        <div class="title flex gap-3">
            <h2 class="text-black font-bold text-4xl mb-3 mt-1">{{ title }}</h2>
            <img src="../assets/logo.svg" alt="" class="w-10 h-12">
        </div>
        <h3 class="text-black font-semibold text-medium nombre">IWISH</h3>
        <div class="info flex justify-between">
            <h4 class="text-gray-600 font-semibold">Desarrollador web <span class="text-violet-700 font-semibold">Front-end</span> </h4>
            <h4 class="text-gray-600 font-semibold">2024</h4>
        </div>
        <p class="mt-4">Mi desempeño en la empresa consistia en ser el encargado de la creación, mantenimiento y optimización de componentes en las paginas web gestionadas por la empresa. Implemente
            tecnologías como HTML, CSS, JavaScript y Bootstrap en Jumpseller para mejorar la experiencia del usuario y el rendimiento del sitio. Implemente soluciones que aumentaron la tasa de conversión.</p>
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
p {
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