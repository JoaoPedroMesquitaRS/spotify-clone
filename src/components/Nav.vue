<template>
    <section class="bg-black max-h-screen text-zinc-400 font-semibold text-lg px-5">
        <div class="">
            <div class="pr-16 py-2 flex w-full">
                <a href="" class="text-4xl">...</a>
            </div>
            <div class="pr-16 py-2 flex w-full items-center hover:text-zinc-50 transition-colors">
                <i class="fa-solid fa-house h-6 pr-2 py-1"></i><a href="">Inicio</a>
            </div>
            <div class="pr-16 py-2 flex w-full items-center hover:text-zinc-50 transition-colors">
                <i class="fa-solid fa-magnifying-glass h-6 pr-2 py-1"></i><a href="">Buscar</a>
            </div>
            <div class="pr-16 py-2 flex w-full items-center hover:text-zinc-50 transition-colors">
                <i class="fa-regular fa-bookmark h-6 pr-2 py-1"></i><a href="">SuaBiblioteca</a>
            </div>
        </div>

        <div class="mt-5 border-b-2 border-zinc-800 ">
            <div class="pr-16 py-2 flex w-full items-center hover:text-zinc-50 transition-colors">
                <i class="fa-solid fa-plus h-6 pr-2 py-1"></i><a href="">CriarPlaylist</a>
            </div>
            <div class="pr-16 py-2 flex w-full items-center hover:text-zinc-50 transition-colors">
                <i class="fa-solid fa-heart h-6 pr-2 py-1"></i><a href="">MúsicasCurtidas</a>
            </div>
            <div class="pr-16 py-2 flex w-full items-center hover:text-zinc-50 transition-colors">
                <i class="fa-regular fa-bookmark h-6 pr-2 py-1"></i><a href="">Seus Episodios</a>
            </div>
        </div>

        <div class="flex flex-col mt-5 text-base font-normal">
            <a class="py-2 hover:text-zinc-50 transition-colors" href="">Playlist 01</a>
            <a class="py-2 hover:text-zinc-50 transition-colors" href="">Playlist 01</a>
            <a class="py-2 hover:text-zinc-50 transition-colors" href="">Playlist 01</a>
            <a class="py-2 hover:text-zinc-50 transition-colors" href="">Playlist 01</a>
            <a class="py-2 hover:text-zinc-50 transition-colors" href="">Playlist 01</a>
            <a class="py-2 hover:text-zinc-50 transition-colors" href="">Playlist 01</a>
        </div>

    </section>
</template>

<script>
    export default{
        name: "Nav"
    }
</script>

<style scoped>

</style>