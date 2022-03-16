<script setup>
import ProjectBlock from '../ProjectBlock.vue';
</script>

<template>
  <section id="projects">
    <div
      class="
        relative
        max-w-5xl
        mx-auto
        pt-10
        pb-10
        sm:pb-42
        lg: lg:pb-52
        sm:pt-14
        lg:pt-22
      "
    >
      <h3 class="text-4xl text-center text-white">
        My <span class="text-blue-500 font-semibold">projects</span>
      </h3>
      <p class="text-xl text-center mt-4 mb-4 text-slate-400">
        With the following projects, all technologies used will be included in the ReadMe found on github.
      </p>

      <div class="container mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-2 sm:gap-10">

            <ProjectBlock 
            projectImg="/img/vuejs-quiz-app.png"
            projectName="VueJs Quiz"
            projectType="Web App"
            liveLink="https://vue-js-quiz.herokuapp.com/"
            sourceLink="https://github.com/IsaacPCooper/Vue-Js-Quiz-App"
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
      <p class="text-xl text-center mt-4 mb-4 text-slate-400">
        Sometimes I upload smaller projects onto CodePen
      </p>
      
    </div>
  </section>
</template>
