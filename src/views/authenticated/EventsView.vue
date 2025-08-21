<script setup>
</script>

<template>
  <main class="min-h-screen bg-gradient-to-br from-blue-50 via-white to-purple-100 px-6 py-16">
    <h1 class="text-4xl font-extrabold text-center text-gray-800 mb-16">📆 Upcoming Events</h1>

    <!-- Event Cards Grid -->
    <div class="grid gap-12 grid-cols-1">
      <!-- Card 1 -->
      <div class="bg-white rounded-3xl shadow-md hover:shadow-xl transition-all p-6 flex flex-col sm:flex-row justify-between border border-gray-100">
        <!-- Left Section: Icon + Date -->
        <div class="flex sm:flex-col items-center justify-between sm:justify-start sm:items-start mb-4 sm:mb-0 sm:mr-6">
          <div class="text-4xl sm:mb-4">💡</div>
          <span class="bg-yellow-100 text-yellow-700 text-xs font-semibold px-3 py-1 rounded-full">Sept 10</span>
        </div>

        <!-- Middle Section: Content -->
        <div class="flex-1 mb-4 sm:mb-0">
          <h3 class="text-xl font-bold text-gray-800 mb-2">Innovation Expo 2025</h3>
          <p class="text-sm text-gray-600">
            Discover creative student projects and emerging technologies reshaping our world.
          </p>
        </div>

        <!-- Right Section: Actions -->
        <div class="flex flex-col sm:items-end justify-between">
          <a href="#" class="text-yellow-600 hover:underline text-sm font-medium mb-2">Learn More</a>
          <button class="bg-yellow-500 text-white text-sm px-4 py-2 rounded-md hover:bg-yellow-600 transition">
            Register
          </button>
        </div>
      </div>

      <!-- Card 2 -->
      <div class="bg-white rounded-3xl shadow-md hover:shadow-xl transition-all p-6 flex flex-col sm:flex-row justify-between border border-gray-100">
        <!-- Left Section -->
        <div class="flex sm:flex-col items-center justify-between sm:justify-start sm:items-start mb-4 sm:mb-0 sm:mr-6">
          <div class="text-4xl sm:mb-4">🎵</div>
          <span class="bg-indigo-100 text-indigo-700 text-xs font-semibold px-3 py-1 rounded-full">Sept 14</span>
        </div>

        <!-- Middle Section -->
        <div class="flex-1 mb-4 sm:mb-0">
          <h3 class="text-xl font-bold text-gray-800 mb-2">Music Under the Stars</h3>
          <p class="text-sm text-gray-600">
            Enjoy a night of live performances from student artists under the campus sky.
          </p>
        </div>

        <!-- Right Section -->
        <div class="flex flex-col sm:items-end justify-between">
          <a href="#" class="text-indigo-600 hover:underline text-sm font-medium mb-2">See Lineup</a>
          <button class="bg-indigo-500 text-white text-sm px-4 py-2 rounded-md hover:bg-indigo-600 transition">
            Attend
          </button>
        </div>
      </div>

      <!-- Card 3 -->
      <div class="bg-white rounded-3xl shadow-md hover:shadow-xl transition-all p-6 flex flex-col sm:flex-row justify-between border border-gray-100">
        <!-- Left Section -->
        <div class="flex sm:flex-col items-center justify-between sm:justify-start sm:items-start mb-4 sm:mb-0 sm:mr-6">
          <div class="text-4xl sm:mb-4">🚀</div>
          <span class="bg-red-100 text-red-600 text-xs font-semibold px-3 py-1 rounded-full">Sept 20</span>
        </div>

        <!-- Middle Section -->
        <div class="flex-1 mb-4 sm:mb-0">
          <h3 class="text-xl font-bold text-gray-800 mb-2">Startup Pitch Night</h3>
          <p class="text-sm text-gray-600">
            Students pitch their big ideas to real investors and mentors for prizes and support.
          </p>
        </div>

        <!-- Right Section -->
        <div class="flex flex-col sm:items-end justify-between">
          <a href="#" class="text-red-500 hover:underline text-sm font-medium mb-2">Details</a>
          <button class="bg-red-500 text-white text-sm px-4 py-2 rounded-md hover:bg-red-600 transition">
            Pitch
          </button>
        </div>
      </div>
    </div>

    <!-- CTA Section -->
    <div class="mt-20 bg-white border border-gray-100 rounded-3xl shadow-md p-10 text-center max-w-2xl mx-auto">
      <h2 class="text-2xl font-bold text-gray-800 mb-3">✨ Host Your Own Event</h2>
      <p class="text-sm text-gray-600 mb-6">
        Got an idea for an amazing event? Submit your proposal and let’s make it happen.
      </p>
      <button class="bg-purple-600 text-white px-6 py-2 rounded-md hover:bg-purple-700 transition text-sm font-semibold">
        Propose Event
      </button>
    </div>
  </main>
</template>