<template>

<div class="border-2 border-black p-4">
    
    <p><b>Buttons:</b></p>
    
    <div class="border border-red-500 p-2">

      <p><u>TailwindCSS</u></p>

      <button type="button" 
      class="shadow-md
      rounded
      bg-gray-100
      px-4
      py-1
      m-1
      font-sans
      hover:bg-gray-200
      active:bg-gray-400">CLICK ME!</button>

      <button type="button" 
      class="shadow-md
      rounded
      bg-yellow-200
      px-4
      py-1
      m-1
      font-sans
      hover:bg-yellow-300
      active:bg-yellow-400">LAMBORGHINI</button>

      <button type="button" 
      class="shadow-md
      rounded
      bg-red-500
      px-4
      py-1
      m-1
      font-sans
      hover:bg-red-600
      active:bg-red-700">FERRARI</button>

      <button type="button" 
      class="shadow-md
      rounded
      bg-green-500
      px-4
      py-1
      m-1
      font-sans
      hover:bg-green-600
      active:bg-green-700">MERCEDES</button>
      
      <button type="button" 
      class="shadow-md
      rounded
      bg-yellow-500
      px-4
      py-1
      m-1
      font-sans
      hover:bg-yellow-600
      active:bg-yellow-700">PORSCHE</button>

    </div>

    <div class="p-1"></div>

    <div class="border border-blue-500 p-2">

    <p><u>Vuetify</u></p>

    <v-btn class="m-1">Click me!</v-btn>
    <v-btn color="yellow" class="m-1">Lamborghini</v-btn>
    <v-btn color="red" class="m-1">Ferrari</v-btn>
    <v-btn color="teal" class="m-1">Mercedes</v-btn>
    <v-btn color="orange" class="m-1">Porsche</v-btn>

    </div>

</div>

</template>