<script>
export default {
    data() {
        return {
            title: 'Proyectos',
        };
    },
}
</script>

<template>
    <main class="mt-10">
        <div class="title flex gap-3">
            <h2 class="text-black font-bold text-4xl mt-1">{{ title }}</h2>
            <img src="../assets/projector-screen.svg" alt="" class="w-10 h-12">
        </div>
        <div class="grid grid-cols-3 gap-10 mt-8 mb-8 text-center">
            <div class="proyecto1 border h-70 rounded-2xl shadow-2xl">
                <div class="title flex justify-around titulo-card" >
                    <div class="cont flex">
                        <div class="bg-green-500 mt-10 rounded-2xl w-4 h-4 circulo-verde"></div>
                        <a href="https://67b4cb613137600cb6c5cd07--preeminent-cactus-154f07.netlify.app/" class="font-bold text-2xl mt-8 mx-2 hover:underline">Gestionador de cursos</a>
                    </div>
                    <a href="https://github.com/matiaasgal/gestionador-cursos-practica" class="mt-8"><img src="../assets/github-logo.svg" alt="github"></a>
                </div>
                <p class="text-start mt-7 text-gray-600 font-semibold text-xl px-6">Proyecto realizado en el curso de VueJS de Talento Digital para Chile. Consiste en un gestor de cursos en el cual se pueden agregar, eliminar y editar cursos. <span class="font-bold text-black">Se utilizó Vue3, VueRouter y Bootstrap</span></p>
            </div>
            <div class="proyecto2 border h-70 rounded-2xl shadow-2xl">
                <div class="title flex justify-around titulo-card">
                    <div class="cont flex">
                        <div class="bg-green-500 mt-10 rounded-2xl w-4 h-4 circulo-verde" id="green-circle"></div>
                        <a href="https://67b4d4eb3137601cc4c5cf08--bucolic-centaur-bf72c2.netlify.app/" class="font-bold text-2xl mt-8 mx-2 hover:underline">Carro de compras de vinos</a>
                    </div>
                    <a href="https://github.com/matiaasgal/vinos-certificaci-n" class="mt-8"><img src="../assets/github-logo.svg" alt="github"></a>
                </div>
                <p class="text-start mt-7 text-gray-600 font-semibold text-xl px-6">Proyecto realizado para la certificacion de el curso de VueJS de Talento Digital para Chile. Consiste en un carro de compras. <span class="font-bold text-black">Se utilizó Vue3, VueRouter, Pinia y Bootstrap</span></p>
                <p class="mt-3 px-4"><span class="text-lg">(Credenciales y pasos a seguir en GitHub)</span></p>
            </div>
        </div>
    </main>
</template>

<style scoped>
.proyecto1, .proyecto2 {
    @media (max-width: 1536px) {
      height: 350px;
    }
}
.proyecto1, .proyecto2 {
    @media (max-width: 1430px) {
      height: 450px;
    }
}
.proyecto1, .proyecto2 {
    @media (max-width: 1280px) {
      height: 350px;
    }
}
.proyecto1, .proyecto2 {
    @media (max-width: 1024px) {
      height: 400px;
    }
}
.proyecto1, .proyecto2 {
    @media (max-width: 768px) {
      height: 500px;
    }
}
.proyecto1, .proyecto2 {
    @media (max-width: 626px) {
      height: 600px;
    }
}
.proyecto1, .proyecto2 {
    @media (max-width: 510px) {
      height: 380px;
    }
}
.proyecto1, .proyecto2 {
    @media (max-width: 434px) {
      height: 480px;
    }
}
.proyecto1, .proyecto2 {
    @media (max-width: 330px) {
      height: 580px;
    }
}
.grid{
    @media (max-width: 1280px) {
        grid-template-columns: repeat(2, 1fr);
        gap: 10px;
    }
}
.grid{
    @media (max-width: 510px) {
        grid-template-columns: repeat(1, 1fr);
        gap: 10px;
    }
}
.title {
    @media (max-width: 581px) {
        justify-content: center;
    }
}

#green-circle {
    @media (max-width: 1280px) {
      margin-left: 25px;
    }
}
.circulo-verde {
    @media (max-width: 1120px) {
      display: none;
    }
}
.titulo-card {
    @media (max-width: 1430px) {
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
  }
</style>