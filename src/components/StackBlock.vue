<script>
export default {
  name: "stackCard",
  props: {
    techImg: {
      type: String,
    },
    techType: {
      type: String,
    },
  },
};
</script>

<template>
  <div class="rounded w-fit">
    <img :src="techImg" height="250" class="bg-white thick-shadow w-full" />
    <p class="text-center text-white text-lg my-2">{{ techType }}</p>
  </div>
</template>