<script setup lang="ts">
</script>

<template>
<div>
<div>
     <Logo />
          <div class="flex flex-col items-center pt-[100px]"> 
               <NuxtLink to="/customerchoice">
                     <button class="bg-white text-purple-element tracking-wide h-16 p-4 font-bold uppercase text-2xl rounded-full">Je commande</button>
               </NuxtLink>
               <NuxtLink to="/whoarewe">
                     <button class="bg-white text-purple-element tracking-wide h-16 p-4 mt-4 font-bold uppercase text-2xl rounded-full">Qui sommes-nous ?</button>
               </NuxtLink>
          </div>
</div>
     <Footer />
</div>
</template>