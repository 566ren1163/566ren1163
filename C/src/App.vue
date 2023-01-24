<script setup>
import ListA from './components/ListA.vue'
import ListB from './components/ListB.vue'



</script>

<template>
  <div class="container">
    <div>
    <ListA class="List1"/>
     <button @click="toggle">右へ移動</button>
    </div>

    <div class="box">
   <ListB class="List2"/>
    <button @click="toggle">左へ移動</button>
  </div>
  </div>

  
  
</template>