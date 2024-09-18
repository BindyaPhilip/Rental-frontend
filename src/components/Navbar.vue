<template>
  <body class="bg-gray-100 h-screen flex justify-center items-center">
  
  <!-- Login Card -->
  <div class="bg-white p-8 rounded-lg shadow-lg w-full max-w-sm">
    <h2 class="text-2xl font-bold text-center mb-6">Login</h2>

    <form action="#">
      <!-- Email Input -->
      <div class="mb-4">
        <label class="block text-gray-700 text-sm font-bold mb-2" for="email">
          Email
        </label>
        <input class="w-full px-3 py-2 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-2 focus:ring-blue-500" 
               type="email" id="email" placeholder="Enter your email">
      </div>

      <!-- Password Input -->
      <div class="mb-6">
        <label class="block text-gray-700 text-sm font-bold mb-2" for="password">
          Password
        </label>
        <input class="w-full px-3 py-2 border border-gray-300 rounded-lg shadow-sm focus:outline-none focus:ring-2 focus:ring-blue-500" 
               type="password" id="password" placeholder="Enter your password">
      </div>

      <!-- Submit Button -->
      <div class="mb-4">
        <button class="w-full bg-blue-500 text-white py-2 rounded-lg hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-blue-500">
          Sign In
        </button>
      </div>

      <!-- Forgot Password -->
      <div class="text-center">
        <a href="#" class="text-sm text-blue-500 hover:underline">Forgot password?</a>
      </div>
    </form>
  </div>

</body>
</template>

<script setup>
//import the logo
import logo from '@/assets/img/logo.png'

</script>

<style>

</style>