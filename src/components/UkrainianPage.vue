<template>
  <iframe :src="ukrainianPageURL" title="Ukrainian Page" frameborder="0" width="100%" />
</template>

<script>
export default {
  name: 'UkrainianPage',
  computed: {
    ukrainianPageURL() {
      // Modify the URL based on the actual file path in the public directory
      return '/Keyo_Home_ua.html';
    },
  },
};
</script>
