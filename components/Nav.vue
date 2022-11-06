<template>
  <nav>
    <ul class="flex gap-5 items-center">
      <li class="p-2 mr-2 cursor-pointer hover:text-amber-400 hover:scale-110">
        <Nuxt-link to="Projects">Projects</Nuxt-link>
      </li>

      <li class="p-2 mr-2 cursor-pointer hover:text-amber-400 hover:scale-110">
        <Nuxt-link to="Graduation">Graduation</Nuxt-link>
      </li>
      <li class="p-2 mr-2 cursor-pointer hover:text-amber-400 hover:scale-110">
        <Nuxt-link to="Skills">Skills</Nuxt-link>
      </li>
      <li>
        <a
          target="_blank"
          rel="noopener noreferrer"
          href="https://www.linkedin.com/in/guibranco/"
        >
          <img
            class="w-7 h-7 cursor-pointer hover:opacity-80 hover:scale-110"
            src="../assets/icons8-linkedin3.svg"
            alt="Linkedin"
        /></a>
      </li>
      <li>
        <a
          target="_blank"
          rel="noopener noreferrer"
          href="https://github.com/Gwhiite"
        >
          <img
            class="w-7 h-7 cursor-pointer hover:opacity-80 hover:scale-110"
            src="../assets/icons8-github3.svg"
            alt="Github"
        /></a>
      </li>
      <li>
        <a
          target="_blank"
          rel="noopener noreferrer"
          href="https://wa.me/55611992039009"
        >
          <img
            class="w-7 h-7 cursor-pointer hover:opacity-80 hover:scale-110"
            src="../assets/icons8-whatsapp3.svg"
            alt="Whatsapp"
        /></a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "Nav",
};
</script>

<style></style>
