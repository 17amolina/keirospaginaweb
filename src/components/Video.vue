<template>
    <!--<div id="video">
        <v-row>
            <v-col>
                Creamos para tí ...
            </v-col>
        </v-row>
    </div>-->
    <v-carousel
    cycle
    height="400"
    hide-delimiter-background
    show-arrows-on-hover
  >
    <v-carousel-item
      v-for="(slide, i) in slides"
      :key="i"
    >
      <v-sheet
        :color="colors[i]"
        height="100%"
      >
        <v-row
          class="fill-height"
          align="center"
          justify="center"
        >
          <div class="display-3">{{ slide }} </div>
        </v-row>
      </v-sheet>
    </v-carousel-item>
  </v-carousel>
    
</template>

<script>
export default {
    name: 'Video',
    data () {
      return {
        colors: [
          '#4C4949',
          '#4C4940',
          '#505153',
          '#454C5C',
          '#2F3D5B',
        ],
        slides: [
          'Creamos para tí ...',
          'Inovamos para tí ...',
          'Diseñamos para tí ...',
          'Imaginamos para tí ...',
          'Trabajamos para tí ...',
        ],
      }
    },
    
}
</script>
<style  scoped>
#video{
    background: #4C4949;
    min-height: 400px;
    color: #ffffff;
}

</style>