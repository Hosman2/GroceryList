<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
const count2 = ref(0)
const count3 = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    Milk
    <button type="button" @click="count++"> + </button>/
    <button type="button" @click="count--"> - </button> :   {{count}}
  </div>
  <div class="card">
    Eggs
    <button type="button" @click="count2++"> + </button>/
    <button type="button" @click="count2--"> - </button> : {{count2}}
  </div>

  <div class="card">
    Bread
    <button type="button" @click="count3++"> + </button>/
    <button type="button" @click="count3--"> - </button> : {{count3}}
  </div>

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
