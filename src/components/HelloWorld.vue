<template>
<v-app>
  <div class="px-4">

    <v-row class="text-center">

      <v-col class="mb-4">

        <h1 class="display-2 font-weight-bold mb-3">
          Welcome to Vue.js Component Styling Showcase
        </h1>

      </v-col>

    </v-row>

    <htmlselect></htmlselect>

    <div class="p-1"></div>

    <buttons></buttons>

    <div class="p-1"></div>

    <textinput></textinput>
    
    <!--<bottomNavigation></bottomNavigation>-->
    
  </div>
</v-app>

</template>

<script>

  //import bottomNavigation from './bottomNavigation';
  import htmlselect from './htmlselect';
  import buttons from './buttons';
  import textinput from './textinput';

  export default {

    name: 'HelloWorld',

    components: {
      //bottomNavigation,
      htmlselect,
      buttons,
      textinput
    },
    
  }
</script>