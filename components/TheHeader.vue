<template>
  <header class="bg-white shadow-sm">
    <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
      <div class="flex items-center">
        <NuxtLink to="/" class="flex items-center">
          <span class="text-2xl font-bold text-blue-600">PaperFreeOffice</span>
        </NuxtLink>
      </div>
      <div class="hidden md:flex space-x-8">
        <NuxtLink to="/" class="text-gray-700 hover:text-blue-600">Home</NuxtLink>
        <NuxtLink to="/services" class="text-gray-700 hover:text-blue-600">Services</NuxtLink>
        <NuxtLink to="/pricing" class="text-gray-700 hover:text-blue-600">Pricing</NuxtLink>
        <NuxtLink to="/contact" class="text-gray-700 hover:text-blue-600">Contact</NuxtLink>
      </div>
    </nav>
  </header>
</template>