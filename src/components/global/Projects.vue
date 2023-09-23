<script setup>
import ProjectBlock from "../ProjectBlock.vue";
</script>

<template>
  <section id="projects">
    <div
      class="relative max-w-5xl mx-auto pt-20 pb-40 sm:pb-42 lg:pb-52 lg:pt-52 sm:pt-24"
    >
      <h3 class="text-4xl text-center text-white">
        My <span class="text-blue-500 font-semibold">projects</span>
      </h3>
      <p class="text-lg text-center mt-4 mb-4 text-slate-400">
        With the following projects, all technologies used will be included in
        the ReadMe found on github.
      </p>

      <div class="container mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-2 sm:gap-10">
          <ProjectBlock
            projectImg="/img/currency-convertor.png"
            projectName="VueJs Currency Convertor"
            projectType="Vue App w/ API Data"
            liveLink="https://comfy-syrniki-b96067.netlify.app/"
            sourceLink="https://github.com/IsaacPCooper/VueJsCurrencyConvertor"
          />

          <ProjectBlock
            projectImg="/img/portfolio.png"
            projectName="This Portfolio"
            projectType="SPA"
            liveLink="#"
            sourceLink="https://github.com/IsaacPCooper/portfolio"
          />
        </div>
      </div>
      <div
        class="bg-white rounded-md thick-shadow border-2 border-blue-500 grid grid-cols-1 justify-center justify-items-center my-8 pt-8 pb-8"
      >
        <p class="text-center mt-4 mb-4">
          Sometimes I upload smaller projects onto CodePen
        </p>
        <a
          class="bg-green-500 hover:bg-blue-500 transition-colors duration-200 p-6 rounded-xl thick-shadow"
          href="https://codepen.io/IsaacPCooper/pens/"
          >Here they are!</a
        >
      </div>
    </div>
  </section>
</template>
