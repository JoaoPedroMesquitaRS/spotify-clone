<template>
    <div class="w-full bg-gradient-to-b from-indigo-950 via-zinc-900 to-zinc-950 px-8 pt-5">
        <section class="w-full">
            <Dash />
            <ForMe />
        </section>
    </div>
</template>

<script>

import Dash from './Dash.vue'
import ForMe from './ForMe.vue'
import Player from './Player.vue'

    export default{
        name: "Main",
        components: {
            Dash,
            ForMe,
            Player
        }
    } 
    
</script>

<style scoped>

</style>