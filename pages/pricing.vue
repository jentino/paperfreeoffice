<template>
  <main class="py-20">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h1 class="text-4xl font-bold text-center mb-12">Pricing Plans</h1>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Basic Plan -->
        <div class="bg-white p-8 rounded-lg shadow-lg border border-gray-200">
          <h2 class="text-2xl font-bold mb-4">Basic</h2>
          <p class="text-4xl font-bold mb-6">$99<span class="text-lg text-gray-600">/month</span></p>
          <ul class="space-y-3 mb-8">
            <li class="flex items-center">
              <span class="text-green-500 mr-2">✓</span>
              Document Management System
            </li>
            <li class="flex items-center">
              <span class="text-green-500 mr-2">✓</span>
              5 User Licenses
            </li>
            <li class="flex items-center">
              <span class="text-green-500 mr-2">✓</span>
              Basic Support
            </li>
          </ul>
          <NuxtLink to="/contact" class="block text-center bg-blue-600 text-white py-2 px-4 rounded-lg hover:bg-blue-700">
            Get Started
          </NuxtLink>
        </div>

        <!-- Professional Plan -->
        <div class="bg-blue-600 text-white p-8 rounded-lg shadow-lg transform scale-105">
          <h2 class="text-2xl font-bold mb-4">Professional</h2>
          <p class="text-4xl font-bold mb-6">$199<span class="text-lg opacity-80">/month</span></p>
          <ul class="space-y-3 mb-8">
            <li class="flex items-center">
              <span class="text-white mr-2">✓</span>
              Document Management System
            </li>
            <li class="flex items-center">
              <span class="text-white mr-2">✓</span>
              Business Process Management
            </li>
            <li class="flex items-center">
              <span class="text-white mr-2">✓</span>
              20 User Licenses
            </li>
            <li class="flex items-center">
              <span class="text-white mr-2">✓</span>
              Priority Support
            </li>
          </ul>
          <NuxtLink to="/contact" class="block text-center bg-white text-blue-600 py-2 px-4 rounded-lg hover:bg-gray-100">
            Get Started
          </NuxtLink>
        </div>

        <!-- Enterprise Plan -->
        <div class="bg-white p-8 rounded-lg shadow-lg border border-gray-200">
          <h2 class="text-2xl font-bold mb-4">Enterprise</h2>
          <p class="text-4xl font-bold mb-6">Custom</p>
          <ul class="space-y-3 mb-8">
            <li class="flex items-center">
              <span class="text-green-500 mr-2">✓</span>
              All Professional Features
            </li>
            <li class="flex items-center">
              <span class="text-green-500 mr-2">✓</span>
              Unlimited Users
            </li>
            <li class="flex items-center">
              <span class="text-green-500 mr-2">✓</span>
              Custom Integration
            </li>
            <li class="flex items-center">
              <span class="text-green-500 mr-2">✓</span>
              24/7 Premium Support
            </li>
          </ul>
          <NuxtLink to="/contact" class="block text-center bg-blue-600 text-white py-2 px-4 rounded-lg hover:bg-blue-700">
            Contact Sales
          </NuxtLink>
        </div>
      </div>
    </div>
  </main>
</template>