<template>
  <!--navigation bar-->
    <div class="bg-white shadow-sm w-full sticky">
      <div class="max-w-6xl mx-auto px-4 py-4 text-gray-700 font-semibold flex flex-row text-lg justify-between items-center">
        <!--left side-->
        <div class="flex flex-row items-baseline">
          <h1 class="text-2xl font-bold pr-2">Justian.dev</h1>
          <NavItem class="cursor-pointer px-2 transition hover:text-purple-600 duration-300" v-for="(item, index) in items" :key="index" :title="item.title"/>
        </div>
        <!--right side-->
        <div class="flex flex-row">
          <a href="" class="bg-purple-600 px-3 py-2 rounded-md text-purple-100 transition duration-300 hover:bg-purple-700"><font-awesome-icon :icon="['fas', 'envelope']" /></a>
          <a href="" class="ml-2 px-3 py-2 rounded-md transition duration-300 hover:bg-gray-200 border"><font-awesome-icon :icon="['fab', 'github']" /></a>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          title: 'About me'
        },
        {
          title: 'Projects'
        }
      ]
    }
  }
}
</script>
