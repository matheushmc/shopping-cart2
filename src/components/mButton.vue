<script setup>

const props = defineProps({
    texto: String
})

</script>

<template>

<button type="button"> {{ props.texto }} </button>

</template>

<style scoped>

button {

background-color: black;
color: white;
border: 2px solid gray;
font-size: 1rem;
border-radius: 5px;
padding:5px 10px;
cursor: pointer;

}

button:hover {
    
    background-color: white;
    color: black;
    border: 2px solid gray;
    font-size: 1rem;
    border-radius: 5px;
    padding: 5px 10px;
    cursor: pointer;
    
}

</style>