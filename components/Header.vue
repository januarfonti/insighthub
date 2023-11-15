<!-- Header component, include brand on the left and others menu on the right, I'm using Nuxtjs 3-->
<template>
  <header class="py-4">
    <div class="container flex items-center justify-between ">
      <NuxtLink to="/" class="font-bold">InsightHub</NuxtLink>
      <nav class="flex items-center gap-10 text-sm">
        <NuxtLink to="#fitur" class="">Tentang</NuxtLink>
        <NuxtLink to="#fitur" class="">Fitur</NuxtLink>
        <NuxtLink to="/faq" class="">FAQ</NuxtLink>
        <NuxtLink to="/dokumentasi" class="">Dokumentasi</NuxtLink>
        <NuxtLink to="/login" class="px-6 py-2 rounded-lg bg-gray-300 font-semibold">Isi Survey</NuxtLink>
      </nav>
    </div>
  </header>
</template>