<template>
  <nav class="bg-gray-800 text-white flex-none">
    <div class="flex justify-between items-center p-4">
      <h1 class="text-2xl font-semibold">Your App</h1>
      <h1 class="text-2xl font-semibold"></h1>
      <h1 class="text-2xl font-semibold">Your App</h1>
      <!-- Toggle Button -->
      <button @click="toggleSidebar" class="block focus:outline-none">
        <svg
          class="w-6 h-6"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16m-7 6h7"
          ></path>
        </svg>
      </button>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<!-- Add your styles here or use an external stylesheet -->
