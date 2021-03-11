<template>
  <div class="bg-gray-900 py-4 flex">
    <div class="px-4 max-w-6xl mx-auto items-center text-center">
      <h1 class="text-5xl text-gray-100 font-semibold"><span class="text-purple-600 text-6xl">{{ title.charAt(0) }}</span>{{ title.slice(1) }}</h1>
    </div>
  </div>
</template>

<script>
  export default {
    props: {
      title: String
    }
  }
</script>
