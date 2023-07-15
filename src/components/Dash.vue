<template>
    <div class="text-zinc-400">
        <a href=""><i id="btn" class="fa-solid fa-angle-left rounded-full py-2 px-3 text-3xl mr-3"></i></a>
        <a href=""><i id="btn" class="fa-solid fa-angle-right rounded-full py-2 px-3 text-3xl mr-3"></i></a>
    </div>
    <div class="flex-col text-white font-semibold text-lg mt-8">
        <h1 class="text-white font-bold text-4xl">Bom dia</h1>
        <div id="cards" class="grid grid-cols-3 gap-7 mt-6">
            <a href="" id="card" class="flex items-center rounded-md">
                <div class="bg-gray-500 px-6 py-8 rounded-s">icone</div>
                <p class="px-4">Musicas curtidas</p>
            </a>
            <a href="" id="card" class="flex items-center rounded-md">
                <div class="bg-gray-500 px-6 py-8 rounded-s">icone</div>
                <p class="px-4">Musicas curtidas</p>
            </a>
            <a href="" id="card" class="flex items-center rounded-md">
                <div class="bg-gray-500 px-6 py-8 rounded-s">icone</div>
                <p class="px-4">Musicas curtidas</p>
            </a>
            <a href="" id="card" class="flex items-center rounded-md">
                <div class="bg-gray-500 px-6 py-8 rounded-s">icone</div>
                <p class="px-4">Musicas curtidas</p>
            </a>
            <a href="" id="card" class="flex items-center rounded-md">
                <div class="bg-gray-500 px-6 py-8 rounded-s">icone</div>
                <p class="px-4">Musicas curtidas</p>
            </a>
            <a href="" id="card" class="flex items-center rounded-md">
                <div class="bg-gray-500 px-6 py-8 rounded-s">icone</div>
                <p class="px-4">Musicas curtidas</p>
            </a>


        </div>
    </div>
    
</template>

<script>
    export default{
        name: "Dash"
    }
</script>

<style scoped>

#card {
    background-color: rgba(78, 78, 78, 0.3);
    color: #fff;
}

#card:hover{

    background-color: rgba(116, 116, 116, 0.3);
    transition: 250ms;
}

#btn {
    background-color: rgba(20, 20, 20, 0.5);
    color: #fff;
}
</style>