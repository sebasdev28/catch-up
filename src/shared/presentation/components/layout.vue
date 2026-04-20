<script setup>

import {Menubar as PvMenubar} from "primevue";
import LanguageSwitcher from "./language-switcher.vue";
</script>

<template>
<div>
  <pv-menubar>
    <template #start>
      <pv-button icon="pi pi-bars" label="CatchUp" text @click="toggleDrawer"/>
    <---! TODO: Add source list --->
    </template>
    <template #end>
      <language-switcher>

      </language-switcher>
    </template>
  </pv-menubar>
</div>

</template>

<style scoped>

</style>