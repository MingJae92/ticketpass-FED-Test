<script setup>
import HelloWorld from "@/components/HelloWorld.vue";
import Navbar from "@/components/Navbar.vue"
import Homepage from "@/components/Homepage.vue"

</script>

<template>

    <div>
      <Navbar/>
      <Pagination/>
      <!--<nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>-->
      <RouterView />
    </div>
  
</template>


 
