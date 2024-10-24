<template>
  <!-- Nuvbra -->
  <div>
<Nuvbar></Nuvbar>
  </div>
  <!-- main -->
  <div class=" my-[100px]">
    <Item></Item>
  </div>

  <!-- Footer -->
   <div>
    
   </div>
</template>

<script setup lang="ts">
import { Ref } from 'vue';
import Nuvbar from '@/layout/Nuvbar.vue';
import Item from '@/components/Item.vue';

</script>

<style scoped>

</style>