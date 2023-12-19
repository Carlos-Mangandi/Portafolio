<template>
    <div class="bg-white min-h-screen sm:p-10 p-5 flex flex-col justify-center dark:bg-[#0F172A] duration-500 transition-all ease-in-out subtle-background">  
      <CardHeader />
      <RouterView />
      <CardFooter /> 
    </div>
</template>

<script lang="ts" setup>
  import CardHeader from './components/CardHeader.vue';
  // import CardFooter from './components/CardFooter.vue';
  </script>

<style>

</style>
