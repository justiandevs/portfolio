<template>
  <div>
    <Header />
    <Hero title="Home" />
    <Nuxt />
  </div>
</template>
<script>
import Header from "../components/Header";
import Hero from "../components/Nav/Hero";
export default {
  components: {Hero, Header}
}
</script>
