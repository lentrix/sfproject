<script setup>
import { RouterLink, RouterView } from 'vue-router'


</script>

<template>
  <div class="flex min-h-[100vh]">
    <div class="w-[320px] bg-gray-900 flex flex-col">
      <div class="heading p-8 bg-green-900">
        <h1 class="text-2xl text-green-200 text-center">
          BENJIE B. LENTERIA
        </h1>
        <div class="text-xl text-gray-300 text-center">
          Semifinal Project
        </div>
      </div>
      <nav class="flex-1 flex flex-col justify-center items-stretched text-center gap-4 text-gray-400">
        <a href="#" class="bg-gray-800 py-4 hover:bg-gray-700 hover:text-white hover:py-5 duration-200">Home</a>
        <a href="#" class="bg-gray-800 py-4 hover:bg-gray-700 hover:text-white hover:py-5 duration-200">Products</a>
        <a href="#" class="bg-gray-800 py-4 hover:bg-gray-700 hover:text-white hover:py-5 duration-200">Categories</a>
        <a href="#" class="bg-gray-800 py-4 hover:bg-gray-700 hover:text-white hover:py-5 duration-200">Transactions</a>
      </nav>
      <div class="p-8 bg-gray-800 text-gray-500 text-center">
        This is a laboratory file 
        intended for training students
        in the use of VueJS 3 created by
        Benjie B. Lenteria for the 
        students of Mater Dei College <br />
        Copyright &copy; 2023.<br />All rights reversed.
      </div>
    </div>
    <div class="main-content bg-green-200 flex-1">
      
    </div>
  </div>
</template>

<style scoped>

</style>
