<template>

<div class="border-2 border-black p-4">
    
    <p><b>Select Component:</b></p>

    <div class="border border-red-500 p-2">

    <p><u>TailwindCSS</u></p>

    <select class="w-full" name="cars" id="cars">
      <option value="none" selected disabled hidden>Choose a car</option>
      <option value="lamborghini">Lamborghini</option>
      <option value="ferrari">Ferrari</option>
      <option value="mercedes">Mercedes</option>
      <option value="Porsche">Porsche</option>
    </select>

    </div>
    <div class="p-1"></div>
    <div class="border border-blue-500 p-2">

    <p><u>Vuetify</u></p>

    <v-select
    :items="items"
    label="Choose a Car"
    >
    </v-select>

    </div>
    
</div>

</template>

<script>

    export default{
        
        data: () =>({
            items: ['Lamborghini', 'Ferrari', 'Mercedes', 'Porsche']
        })
        
    }

</script>