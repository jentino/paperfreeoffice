<template>
  <footer class="bg-gray-800 text-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
        <div>
          <h3 class="text-lg font-semibold mb-4">PaperFreeOffice</h3>
          <p class="text-gray-400">Transform your business with our digital solutions.</p>
        </div>
        <div>
          <h4 class="text-lg font-semibold mb-4">Services</h4>
          <ul class="space-y-2">
            <li><NuxtLink to="/services#dms" class="text-gray-400 hover:text-white">Document Management</NuxtLink></li>
            <li><NuxtLink to="/services#bpm" class="text-gray-400 hover:text-white">Business Process Management</NuxtLink></li>
            <li><NuxtLink to="/services#digitization" class="text-gray-400 hover:text-white">Digitization Services</NuxtLink></li>
          </ul>
        </div>
        <div>
          <h4 class="text-lg font-semibold mb-4">Company</h4>
          <ul class="space-y-2">
            <li><NuxtLink to="/about" class="text-gray-400 hover:text-white">About Us</NuxtLink></li>
            <li><NuxtLink to="/contact" class="text-gray-400 hover:text-white">Contact</NuxtLink></li>
          </ul>
        </div>
        <div>
          <h4 class="text-lg font-semibold mb-4">Contact</h4>
          <ul class="space-y-2 text-gray-400">
            <li>Email: info@paperfreeoffice.com</li>
            <li>Phone: (555) 123-4567</li>
          </ul>
        </div>
      </div>
      <div class="mt-8 pt-8 border-t border-gray-700 text-center text-gray-400">
        <p>&copy; {{ new Date().getFullYear() }} PaperFreeOffice. All rights reserved.</p>
      </div>
    </div>
  </footer>
</template>