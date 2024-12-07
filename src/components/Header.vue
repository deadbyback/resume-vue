<template>
  <header class="flex items-center space-x-8 mb-8">
    <div class="flex-shrink-0 w-40 h-40">
      <img
        src="@/assets/personal.jpg"
        alt="Your Photo"
        class="w-full h-full object-cover rounded-full border-4 border-white shadow-md"
      />
    </div>
    <div>
      <h1 class="text-4xl font-bold tracking-wide text-gray-900 mb-2">
        OLEKSANDR VANIN
      </h1>
      <p class="uppercase tracking-widest text-gray-500">
        PHP Backend / Fullstack Developer
      </p>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>
