<template>
    <div class="text-center">
        <v-row>
            <v-btn text rounded dark id="menu">Inicio</v-btn>
            <v-btn rounded dark id="menu">Nosotros</v-btn>
            <v-btn rounded dark id="menu">Diseño</v-btn>
            <v-btn rounded dark id="menu">Impresión</v-btn>
            <v-btn rounded dark id="menu">Web</v-btn>
            <v-btn rounded dark id="menu">Revista de volada</v-btn>
            <v-btn rounded dark id="menu">Contacto</v-btn>
        </v-row>
    </div>    
</template>

<script>
export default {
    name: 'Menu'
    
}
</script>

<style scoped>
#menu{
    margin:2px;
}
#menu:hover{
    background: #49A942;
}
</style>