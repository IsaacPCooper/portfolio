<script>
export default {
  name: "ProjectBlock",
  props: {
    projectImg: {
      type: String,
    },
    projectName: {
      type: String,
    },
    projectType: {
      type: String,
    },
    liveLink: {
      type: String,
    },
    sourceLink: {
      type: String,
    },
  },
};
</script>

<template>
  <div class="bg-white rounded-md thick-shadow border-2 border-blue-500 my-2">
    <div>
      <img
        :src="projectImg"
        height="780"
        width="780"
        class="border-b-2 border-blue-500 shadow-sm"
      />
    </div>
    <div class="py-4">
      <p class="text-center text-2xl">{{ projectName }}</p>
      <p class="text-center text-lg">{{ projectType }}</p>
    </div>

    <div class="grid grid-cols-2 justify-items-center justify-center pb-10">
      <a
        :href="liveLink"
        target="new"
        class="bg-green-500 p-4 rounded-xl thick-shadow"
        >Live Example</a
      >

      <a
        :href="sourceLink"
        target="new"
        class="bg-blue-500 p-4 rounded-xl thick-shadow"
        >Source Code</a
      >
    </div>
  </div>
</template>
