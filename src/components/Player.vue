<template>
    <section id="player" class="border-t-2 border-zinc-800 flex justify-between items-center text-zinc-400 font-semibold bg-zinc-900 box-border 
    px-5 py-3 w-full">
        <div id="song" class="flex items-center">
            <img class="bg-gray-700 py-8 mr-3" style="background-image: url('/src/img/cover01.JPG'); 
            background-repeat: no-repeat; background-size: contain; width: 64px; height: 0;">
            <div class="flex flex-col">
                <a href="" class="w-36 text-zinc-200 hover:underline">Song song song 01</a>
                <a href="" class="hover:underline text-gray-500 text-xs">Artist</a>
            </div>
            <i class="fa-solid fa-heart px-3 h-5" style="color: #48df34;"></i>
        </div>

        <div id="atr" class="flex flex-col items-center gap-3 mt-3">
            <div>
                <i class="fa-solid fa-shuffle mx-5 h-6 hover:text-zinc-200 transition-color"></i>
                <i class="fa-solid fa-backward-step mx-5 h-6 hover:text-zinc-200 transition-color"></i>
                <i class="fa-solid fa-play mx-5 h-6 hover:text-zinc-200 transition-color"></i>
                <i class="fa-solid fa-forward-step mx-5 h-6 hover:text-zinc-200 transition-color"></i>
                <i class="fa-solid fa-repeat mx-5 h-6 hover:text-zinc-200 transition-color"></i>
            </div>
            <div class="gap-3 flex items-center text-sm font-normal text-zinc-400">
                <span>0:30</span>
                <div class="h-1 rounded-full w-96 bg-zinc-600">
                    <div class="h-1 rounded-full w-44 bg-zinc-100"></div>
                </div>
                <span>2:30</span>
            </div>
        </div>

        <div id="det">
            <a href=""><i class="fa-solid fa-microphone mx-2 h-5 hover:text-zinc-200 transition-color"></i></a>
            <a href=""><i class="fa-solid fa-list mx-2 h-5 hover:text-zinc-200 transition-color"></i></a>
            <a href=""><i class="fa-solid fa-expand mx-2 h-5 hover:text-zinc-200 transition-color"></i></a>
        </div>
    </section>
</template>

<script>
    
</script>

<style scoped>

#player{

    position:fixed;
    bottom:0;

}

</style>