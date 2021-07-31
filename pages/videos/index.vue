<template>
  <div>
    <h1>Videos</h1>
    <div v-for="video in videos" :key="video.id">
      <h3>{{ video.name }}</h3>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      videos: [
        {
          id: 16,
          name: "Introduction to Nuxt JS",
        },
        {
          id: 19,
          name: "Introduction to Vue JS",
        },
        {
          id: 71,
          name: "Introduction to JS",
        },
      ],
    };
  },
};
</script>

<style>
</style>
