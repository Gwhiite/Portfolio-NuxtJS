<template>
  <div
    class="container mx-auto font-mono text-lg antialiased text-slate-100 box-border"
  >
    <Header />
    <section class="flex flex-col items-center">
      <div class="flex items-center gap-32 mb-14">
        <div class="text-lg text-left leading-relaxed max-w-xl">
          <h1 class="mb-10 text-3xl border-b-2 border-amber-400 inline-block">
            Guilherme Branco De Campos
          </h1>
          <p>
            Entusiasta da área de tecnologia. Aos 17 anos, comecei a desenvolver
            e me identifiquei com a área desde o princípio. Além de desenvolver,
            também busquei adiquirir soft skills para me tornar útil em vários
            sentidos dentro da área. Sempre fui muito comunicativo e proativo,
            gosto de planejar bem as coisas antes de realizá-las<span
              class="text-amber-400"
              >.</span
            >
          </p>
        </div>
        <img
          class="max-w-xs rounded-full"
          src="../assets/perfil.jpg"
          alt="Perfil"
        />
      </div>
    </section>
  </div>
</template>

<script>
import Nav from "../components/Nav.vue";
export default {
  name: "IndexPage",
};
</script>
<style>
body {
  background-color: rgb(15 23 42);
}
</style>
