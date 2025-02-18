<script>
export default {
    data() {
        return {
        };
    },
}
</script>

<template>
    <main class="mt-6">
        <div class="title flex gap-3">
            <h2 class="text-black font-bold text-4xl mt-1 mb-4">Sobre mi</h2>
            <img src="../assets/user.svg" alt="" class="w-10 h-12">
        </div>
        <h4 class="text-black font-medium">Soy alguien <span class="text-violet-700 font-semibold">comprometido y altamente responsable</span>, poseo la capacidad de adaptarme eficazmente a diversas actividades y sectores. Mi <span class="text-violet-700 font-semibold">fuerte compromiso con el desarrollo</span> se refleja en mi disposición para desempeñarme de la mejor manera en el área donde me encuentre.<span class="text-violet-700 font-semibold"> Estoy listo para enfrentar desafíos </span>con dedicación y contribuir al éxito en cualquier entorno laboral. Actualmente soy egresado de bootcamp de <span class="text-violet-700 font-semibold">Desarrollo de Aplicaciones Web con Vue3 de Sence</span> y me encuentro estudiando <span class="text-violet-700 font-semibold"> Analista en Ciencias Computacionales</span> en la <span class="text-violet-700 font-semibold">Universidad de Santiago de Chile</span>.</h4>
    </main>
</template>

<style scoped>
h4 {
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