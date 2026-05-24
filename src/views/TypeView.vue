<script setup>
import Type from "../components/Types.vue"
const arrayOfTypes = ["Mazda","Infiniti","Dodge"];
</script>

<template>
<div class="ml-2 flex gap-2">
  <Type v-for="(item,index) in arrayOfTypes" v-bind:id="index" :title="item"></Type>
</div>
  <p class="ml-2 text-gray-300"> Марки машин которые мне симпатизируют </p>


</template>

<style scoped>

</style>