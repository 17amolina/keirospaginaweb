<template>
    <v-container
    fluid=""
    >
    <v-app-bar
      color="#000000"
      absolute="true"
      min-height="100px"
    >
    <img src="" alt="">
      <v-spacer></v-spacer>
      <ul>
          <li>Inicio</li>
          <li>Nosotros</li>
          <li>Diseño</li>
          <li>Impresión</li>
          <li>Web</li>
          <li>Revista de volada</li>
          <li>Contacto</li>
      </ul>

      
    </v-app-bar>
    </v-container>
</template>

<script>
export default {
    name: 'Barranav'
    
}
</script>

<style scoped>
li{
    display: inline;
    color: #ffffff;
    padding: 20px;
    position: relative;
}
li:hover{
    background: #49A942;
    border-radius: 10px;
}

</style>