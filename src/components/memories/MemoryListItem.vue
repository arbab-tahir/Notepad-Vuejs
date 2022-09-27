<template>
  <ion-item :router-link="`/memories/${memory.id}`">
    <ion-label>
      {{ memory.title }}
    </ion-label>
  </ion-item>
</template>

<script>
import { IonItem, IonLabel } from "@ionic/vue";

export default {
  props: ["memory"],
  components: {
    IonItem,
    IonLabel,
  },
};
</script>
