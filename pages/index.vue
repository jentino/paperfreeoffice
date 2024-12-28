<template>
  <main>
    <HeroSection />
    <!-- Services Section -->
    <section class="py-20">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-bold text-center mb-12">Our Services</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="bg-white p-6 rounded-lg shadow-lg">
            <h3 class="text-xl font-semibold mb-4">Document Management System</h3>
            <p class="text-gray-600 mb-4">Organize, store, and retrieve your documents efficiently with our advanced DMS.</p>
            <NuxtLink to="/services#dms" class="text-blue-600 hover:text-blue-800">Learn more →</NuxtLink>
          </div>
          <div class="bg-white p-6 rounded-lg shadow-lg">
            <h3 class="text-xl font-semibold mb-4">Business Process Management</h3>
            <p class="text-gray-600 mb-4">Automate and optimize your business processes for maximum efficiency.</p>
            <NuxtLink to="/services#bpm" class="text-blue-600 hover:text-blue-800">Learn more →</NuxtLink>
          </div>
          <div class="bg-white p-6 rounded-lg shadow-lg">
            <h3 class="text-xl font-semibold mb-4">Digitization Services</h3>
            <p class="text-gray-600 mb-4">Convert your paper documents into searchable digital formats.</p>
            <NuxtLink to="/services#digitization" class="text-blue-600 hover:text-blue-800">Learn more →</NuxtLink>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>