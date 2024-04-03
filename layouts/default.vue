<script setup>
const links = [
  {
    label: 'Home',
    to: '/'
  },
  {
    label: 'About',
    to: '/about'
  }
]
</script>


<template>
<div class='flex flex-col'>
  
  <UHorizontalNavigation class="border-b border-gray-400" :links="links"/>
  <UContainer>
  <div class='p-10 bg-red-900'>
  <slot />
  </div>
  </UContainer>
  
</div>
</template>
