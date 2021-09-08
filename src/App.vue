<template>
  <Footer />
  <router-view />
  <Header />
</template>

<script>
import Footer from "@/components/Footer";
import Header from "@/components/Header";
export default {
  components: {
    Footer,
    Header,
  },
};
</script>

<style lang="scss">
</style>
