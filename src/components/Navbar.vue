<script setup>
  import { RouterLink, RouterView } from 'vue-router'
</script>
<template>
  <nav>
  <div class="container mx-auto">
    <div class="sm:flex justify-around">
      <!-- Site-title  -->
      <RouterLink to="/"><a href="#" class="text-red text-3xl font-bold p-3">ticketpass</a></RouterLink>

      <!-- Menus  -->
      <ul class="text-blue-400 sm:self-center text-xl border-t sm:border-none">
        <li class="sm:inline-block">
         <RouterLink to="/createevent"><a href="#" class="p-3 hover:text-black">CREATE EVENT</a></RouterLink> 
        </li>
        <li class="sm:inline-block">
          <RouterLink to="/login"><a href="#" class="p-3 hover:text-black">LOG IN</a></RouterLink>
        </li>
       
      </ul>
    </div>
  </div>
</nav>

</template>

