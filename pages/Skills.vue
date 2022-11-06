<template>
  <div
    class="container mx-auto font-mono text-lg antialiased text-slate-100 box-border"
  >
    <Header />
    <div class="flex flex-col items-center justify-center">
      <h2 class="mb-20 text-2xl border-b-2 border-amber-400 inline-block">
        Skills
      </h2>
      <div class="grid grid-cols-11 grid-rows-1 gap-3 place-items-center">
        <div class="flex gap-16 mb-4 col-span-11 border-b-2 border-amber-200">
          <div class="flex items-center justify-center flex-col">
            <img
              class="w-9 h-9 cursor-pointer hover:opacity-80 hover:scale-110"
              src="../assets/html.svg"
              alt="html"
            />
            <p>HTML</p>
          </div>
          <div class="flex items-center justify-center flex-col">
            <img
              class="w-9 h-9 cursor-pointer hover:opacity-80 hover:scale-110"
              src="../assets/js.svg"
              alt="javascript"
            />
            <p>JavaScript</p>
          </div>
          <div class="flex ml-2 items-center justify-center flex-col">
            <img
              class="w-9 h-9 cursor-pointer hover:opacity-80 hover:scale-110"
              src="../assets/css.svg"
              alt="css"
            />
            <p>CSS</p>
          </div>
        </div>
        <div
          class="flex gap-16 mb-4 col-span-11 items-center border-b-2 border-lime-300"
        >
          <div class="flex items-center justify-center flex-col">
            <img
              class="w-9 h-9 cursor-pointer hover:opacity-80 hover:scale-110"
              src="../assets/nuxtjs.svg"
              alt="nuxtjs"
            />
            <p>NuxtJS</p>
          </div>
          <div class="flex items-center justify-center flex-col">
            <img
              class="w-9 h-9 cursor-pointer hover:opacity-80 hover:scale-110"
              src="../assets/vuejs.svg"
              alt="vuejs"
            />
            <p>VueJS</p>
          </div>
          <div class="flex items-center justify-center flex-col">
            <img
              class="w-9 h-9 cursor-pointer hover:opacity-80 hover:scale-110"
              src="../assets/tailwind.svg"
              alt="tailwindcss"
            />
            <p>Tailwind</p>
          </div>
        </div>
        <div
          class="flex gap-16 mb-4 col-span-11 items-cente border-b-2 border-sky-500"
        >
          <div class="flex items-center justify-center flex-col">
            <img
              class="w-9 h-9 cursor-pointer hover:opacity-80 hover:scale-110"
              src="../assets/django.svg"
              alt="django"
            />
            <p>Django</p>
          </div>
          <div class="flex items-center justify-center flex-col">
            <img
              class="w-9 h-9 cursor-pointer hover:opacity-80 hover:scale-110"
              src="../assets/python.svg"
              alt="python"
            />
            <p>Python</p>
          </div>
          <div class="flex items-center justify-center flex-col">
            <img
              class="w-9 h-9 cursor-pointer hover:opacity-80 hover:scale-110"
              src="../assets/db.svg"
              alt="db"
            />
            <p>Database</p>
          </div>
        </div>
        <div
          class="flex gap-16 mb-4 col-span-11 items-center border-b-2 border-red-700"
        >
          <div class="flex items-center justify-center flex-col">
            <img
              class="w-9 h-9 cursor-pointer hover:opacity-80 hover:scale-110"
              src="../assets/npm.svg"
              alt="npm"
            />
            <p>NPM</p>
          </div>
          <div class="flex items-center justify-center flex-col">
            <img
              class="w-9 h-9 cursor-pointer hover:opacity-80 hover:scale-110"
              src="../assets/icons8-github3.svg"
              alt="github"
            />
            <p>Github</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
body {
  background-color: rgb(15 23 42);
}
</style>
