<script>
export default {
    data() {
        return {
            name: 'Matias D. Galiano Lazo',
            title: 'Licenciado en Ciencias de la Computación',
            title2: 'Desarrollador Front-End',
            city: 'Santiago, Chile, CL'
        };
    },
}
</script>

<template>
    <main>
        <div class="top">
            <h1 class="text-5xl mt-30 text-black font-bold">{{ name }}</h1>
            <h3 class="text-2xl text-violet-500 font-mediu">{{ title2 }}</h3>
        </div>
        <div class="mid mt-4 flex ">
            <img src="../assets/planeta.svg" alt="World">
            <h4 class="text-gray-800 mx-2 mt-1">{{ city }}</h4>
        </div>
        <div class="bot mt-8 flex gap-5">
            <button><a href="mailto:matias.gal63@gmail.com"><img class="w-10 h-14" src="../assets/mail.svg" alt=""></a></button>
            <button><a href="https://github.com/matiaasgal"><img class="w-10 h-14" src="../assets/github-logo.svg" alt=""></a></button>
            <button><a href="https://www.linkedin.com/in/matias-galiano-lazo-3a542331a/"><img class="w-10 h-14" src="../assets/linkedin-logo.svg" alt=""></a></button>
            <button><a href="https://wa.me/56975476965"><img class="w-10 h-14" src="../assets/wsp-logo.svg" alt=""></a></button>

        </div>
    </main>
</template>

<style scoped>
.top > h1 {
    @media (max-width: 581px) {
        font-size: 40px;
        text-align: center;
    }
}
.top > h1 {
    @media (max-width: 485px) {
        margin-bottom: 30px;
        font-size: 35px;
        text-align: center;
    }
}
.top > h2, .top > h3 {
    @media (max-width: 581px) {
        text-align: center;
    }
}
 .mid {
    @media (max-width: 581px) {
        justify-content: center;
    }
}
 .bot {
    @media (max-width: 581px) {
        justify-content: center;
    }
}
</style>