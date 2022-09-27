<template>
  <h2 class="ion-text-center">{{ title }}</h2>
  <p class="ion-text-center">{{ description }}</p>
</template>

<script>
export default {
  props: ["title", "image", "description"],
  components: {},
};
</script>
