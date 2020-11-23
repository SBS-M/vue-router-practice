<template>
    <div class="container">
        <h1>Informacion de usuarios</h1>

        <router-link :to="item" v-for="item in listUsuarios" :key="item">
            <button>{{ item }}</button>
        </router-link>
        <Usuario/>
    </div>
</template>

<script>
import Usuario from '@/components/Usuario.vue'

export default {
    name: 'Usuarios',
    components: {
        Usuario
    },
    data() {
        return {
            listUsuarios: ['grover', 'sofia', 'karla']
        }
    },
}
</script>

<style>
    
</style>