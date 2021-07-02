<template>

  <v-container>

    <v-row class="text-center">

      <v-col cols="12">

        <v-img
          :src="require('../assets/logo.svg')"
          class="my-3"
          contain
          height="200"
        />

      </v-col>

      <v-col class="mb-4">

        <h1 class="display-2 font-weight-bold mb-3">
          Welcome to Vue.js Component Styling Showcase
        </h1>

      </v-col>

    </v-row>

    <p>Select Component:</p>

    <div class="border">

    <p class="font-weight-bold">TailwindCSS</p>

    <select class="w-full" name="cars" id="cars">
      <option value="none" selected disabled hidden>Choose a car</option>
      <option value="lamborghini">Lamborghini</option>
      <option value="ferrari">Ferrari</option>
      <option value="mercedes">Mercedes</option>
      <option value="Porsche">Porsche</option>
    </select>

    </div>
    
    <div class="border">

    <p class="font-weight-bold">Vuetify</p>

    <v-select
    :items="items"
    label="Choose a Car"
    >
    </v-select>

    </div>

    <p>Buttons:</p>

    <div class="border">

      <p class="font-weight-bold">TailwindCSS</p>

      <button type="button" 
      class="shadow-md
      bg-gray-100
      px-4
      py-1
      hover:bg-gray-200
      active:bg-gray-400">CLICK ME!</button>

    </div>

    <div class="border">

    <p class="font-weight-bold">Vuetify</p>

    <v-btn>Click me!</v-btn>

    </div>

  </v-container>

</template>

<script>

  export default {

    name: 'HelloWorld',

    data: () =>({
      items: ['Lamborghini', 'Ferrari', 'Mercedes', 'Porsche']
    })
    
  }
</script>