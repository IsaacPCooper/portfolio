<script setup>
import StackBlock from "./StackBlock.vue";
</script>
<template>
  <section id="myStack">
    <div
      class="relative max-w-5xl mx-auto pt-20 pb-40 sm:pb-42 lg:pb-52 lg:pt-52 sm:pt-24"
    >
      <h3 class="text-4xl text-white">
        My <span class="text-blue-500 font-semibold text-shadow">Stack</span>
      </h3>
      <p class="text-lg mt-4 mb-4 text-slate-400">
        I have experience using the following technologies
      </p>

      <div class="container mx-auto">
        <div class="grid grid-cols-2 md:grid-cols-4 gap-10">
          <StackBlock techImg="/img/vuelogo.png" techType="Vue.JS" />

          <StackBlock techImg="/img/angularLogo.png" techType="Angular" />

          <StackBlock techImg="/img/tailwindlogo.png" techType="Tailwind CSS" />

          <StackBlock techImg="/img/gitlogo.png" techType="Git" />

          <StackBlock techImg="/img/WPlogo.png" techType="WordPress" />

          <StackBlock techImg="/img/JSlogo.png" techType="JavaScript" />

          <StackBlock techImg="/img/TSlogo.png" techType="TypeScript" />

          <StackBlock techImg="/img/nodelogo.png" techType="Node.JS" />
        </div>
      </div>
    </div>
  </section>
</template>
