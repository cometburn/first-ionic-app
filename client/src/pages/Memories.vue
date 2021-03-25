<template>
  <base-layout page-title="All Memories">
      <ion-list>
        <ion-item router-link="/memories/1">1</ion-item>
        <ion-item router-link="/memories/2">2</ion-item>
        <ion-item router-link="/memories/3">3</ion-item>
        <ion-item router-link="/memories/4">4 </ion-item>
      </ion-list>
  </base-layout>
</template>

<script>
import { IonList, IonItem } from "@ionic/vue";
import BaseLayout from "@/components/BaseLayout.vue";

export default {
    components: {
        IonList,
        IonItem,
        BaseLayout,
    },
};
</script>