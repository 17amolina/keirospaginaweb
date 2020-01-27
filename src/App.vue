<template>
  <v-app>
    <v-app-bar
      app
      color="black"
      min-height="90"
    >
      <div>
        <img id="logo" src="./assets/keiros-logo.png" alt="">
    </div>
      <v-spacer></v-spacer>
      <Menu/>
    </v-app-bar>
    
    <v-content>
      <div>
        <v-row id="linea">
          <v-col></v-col>
        </v-row>
      </div>
      <Video/>
      <div>
        <v-row id="linea2">
          <v-col></v-col>
        </v-row>
      </div>
      <div>
        <v-row id="linea3">
          <v-col></v-col>
        </v-row>
      </div>
    </v-content>
    <v-footer
      color="black"
      app
    >
      <span class="white--text">&copy; 2019</span>
    </v-footer>
  </v-app>
</template>

<script>
import Menu from './components/Menu'
import Video from './components/Video'


export default {
  name: 'App',

  components: {
    Menu,
    Video,
  },
   props: {
      source: String,
    },
    data: () => ({
      drawer: null,
    }),
};
</script>

<style scoped>
#logo{
    margin-left: 50px;
    margin-top: 60px;
}
#linea{
    background: #49A942;
    min-height: 35px
}
#linea2{
    background: #0d0d11;
    min-height: 5px;
}
#linea3{
    background: #A0CC3A;
    min-height: 80px;
}

</style>
