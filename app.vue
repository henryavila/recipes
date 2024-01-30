<template>
  <div>
    <div class="bg-slate-700 py-3 px-1 flex items-center">
      <img src="/logo.png">
      <div class="text-white text-2xl ml-3 hidden sm:inline-block">
        Receitas selecionadas
      </div>
    </div>
    <iframe ref="recipes" class="absolute h-full w-full transparent" src="/paprika"/>
  </div>
</template>


<script setup>
useHead({
  title: 'Receitas do Henry Ávila',
  ogImage: '/favicon.png',
  favicon: '/favicon.png',
  bodyAttrs: {
    class: 'wrapper relative min-h-screen w-full blurredBg bg-slate-100',

  }
})
</script>

