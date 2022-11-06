<template>
  <header class="flex items-center justify-between mt-14 mb-32">
    <Nuxt-link to="/">
      <div
        class="text-3xl cursor-pointer flex items-center gap-3 hover:text-amber-400 hover:scale-110"
      >
        <img
          class="w-10 h-10"
          src="../assets/avatar-batman-comicsrepo-com.svg"
          alt="Logo"
        />
        <h1>Branco</h1>
      </div>
    </Nuxt-link>

    <Nav />
  </header>
</template>

<script>
import Nav from "./Nav.vue";
export default {
  name: "Header",
  components: {
    Nav,
  },
};
</script>

<style></style>
