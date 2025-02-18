<script>
export default {
    data() {
        return {
            title: 'Habilidades',
        };
    },
}
</script>

<template>
    <main class="mt-10">
        <div class="title flex gap-3">
            <h2 class="text-black font-bold text-4xl mt-1">{{ title }}</h2>
            <img src="../assets/keyboard.svg" alt="">
        </div>
        <div class="botones mt-3">
            <ul class="grid grid-cols-8 gap-4 mt-4 text-center">
                <li class="border border-purple-400 transition duration-500 cursor-pointer rounded-2xl bg-white hover:border-0 hover:bg-violet-600 hover:text-white  hover:scale-103 focus:outline-2 focus:outline-offset-2 focus:outline-violet-700 active:bg-violet-700 "><div class="p-1 font-semibold">JavaScript</div></li>
                <li class="border border-purple-400 transition duration-500 cursor-pointer rounded-2xl bg-white hover:border-0 hover:bg-violet-600 hover:text-white  hover:scale-103 focus:outline-2 focus:outline-offset-2 focus:outline-violet-700 active:bg-violet-700 "><div class="p-1 font-semibold">Python</div></li>
                <li class="border border-purple-400 transition duration-500 cursor-pointer rounded-2xl bg-white hover:border-0 hover:bg-violet-600 hover:text-white  hover:scale-103 focus:outline-2 focus:outline-offset-2 focus:outline-violet-700 active:bg-violet-700 "><div class="p-1 font-semibold">NodeJS</div></li>
                <li class="border border-purple-400 transition duration-500 cursor-pointer rounded-2xl bg-white hover:border-0 hover:bg-violet-600 hover:text-white  hover:scale-103 focus:outline-2 focus:outline-offset-2 focus:outline-violet-700 active:bg-violet-700 "><div class="p-1 font-semibold">VueJS</div></li>
                <li class="border border-purple-400 transition duration-500 cursor-pointer rounded-2xl bg-white hover:border-0 hover:bg-violet-600 hover:text-white  hover:scale-103 focus:outline-2 focus:outline-offset-2 focus:outline-violet-700 active:bg-violet-700 "><div class="p-1 font-semibold">MySQL</div></li>
                <li class="border border-purple-400 transition duration-500 cursor-pointer rounded-2xl bg-white hover:border-0 hover:bg-violet-600 hover:text-white  hover:scale-103 focus:outline-2 focus:outline-offset-2 focus:outline-violet-700 active:bg-violet-700 "><div class="p-1 font-semibold">Tailwind</div></li>
                <li class="border border-purple-400 transition duration-500 cursor-pointer rounded-2xl bg-white hover:border-0 hover:bg-violet-600 hover:text-white  hover:scale-103 focus:outline-2 focus:outline-offset-2 focus:outline-violet-700 active:bg-violet-700 "><div class="p-1 font-semibold">Bootstrap</div></li>
                <li class="border border-purple-400 transition duration-500 cursor-pointer rounded-2xl bg-white hover:border-0 hover:bg-violet-600 hover:text-white  hover:scale-103 focus:outline-2 focus:outline-offset-2 focus:outline-violet-700 active:bg-violet-700 "><div class="p-1 font-semibold">Git</div></li>
                <li class="border border-purple-400 transition duration-500 cursor-pointer rounded-2xl bg-white hover:border-0 hover:bg-violet-600 hover:text-white  hover:scale-103 focus:outline-2 focus:outline-offset-2 focus:outline-violet-700 active:bg-violet-700 "><div class="p-1 font-semibold">GitHub</div></li>
                <li class="border border-purple-400 transition duration-500 cursor-pointer rounded-2xl bg-white hover:border-0 hover:bg-violet-600 hover:text-white  hover:scale-103 focus:outline-2 focus:outline-offset-2 focus:outline-violet-700 active:bg-violet-700 "><div class="p-1 font-semibold">HTML</div></li>
                <li class="border border-purple-400 transition duration-500 cursor-pointer rounded-2xl bg-white hover:border-0 hover:bg-violet-600 hover:text-white  hover:scale-103 focus:outline-2 focus:outline-offset-2 focus:outline-violet-700 active:bg-violet-700 "><div class="p-1 font-semibold">CSS</div></li>
                <li class="border border-purple-400 transition duration-500 cursor-pointer rounded-2xl bg-white hover:border-0 hover:bg-violet-600 hover:text-white  hover:scale-103 focus:outline-2 focus:outline-offset-2 focus:outline-violet-700 active:bg-violet-700 "><div class="p-1 font-semibold">Sass</div></li>
            </ul>
        </div>
    </main>
</template>

<style scoped>
.grid{
    @media (max-width: 1024px) {
        grid-template-columns: repeat(4, 2fr);
        gap: 10px;
    }
}
.grid{
    @media (max-width: 500px) {
        grid-template-columns: repeat(2, 1fr);
        gap: 10px;
    }
}
.title {
    @media (max-width: 581px) {
        justify-content: center;
    }
}
</style>