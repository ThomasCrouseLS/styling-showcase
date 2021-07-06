<template>

<div class="border-2 border-black px-4">
    <p><b>Text Field:</b></p>
    <div class="border border-red-500">
        <p><u>TailwindCSS</u></p>
        <form class="w-full px-4">
            <label for="make">Car Make:</label>
            <input type="text" id="make" name="make"><br><br>
            <label for="model">Car Model:</label>
            <input type="text" id="model" name="model"><br><br>
        </form>
    </div>
    <div class="border border-blue-500">
        <p><u>Vuetify</u></p>
        <v-text-field class="px-4" label="Car Make"></v-text-field>
        <v-text-field class="px-4" label="Car Model"></v-text-field>
    </div>
</div>

</template>
