<script setup>
import {useI18n} from 'vue-i18n';
const {t}= useI18n();
</script>

<template>
<div class="grid bg-primary mt-4 align-content-start">
  <div class="col-12 ml-3 align-items-center justify-content-center">
    <p>Copyright &copy; 2026 ACME Studios</p>
  </div>
  <div class="col-12 ml-3 mt-3 align-items-center justify-content-center">
    <p>
      {{t('authoring-phrase.intro')}} <i class="pi pi-heart"/>
      {{t('authoring-phrase.use')}} <a href="https://primevue.org/" target="_blank">Prime Vue.js</a>.
      {{t('authoring-phrase.author',{brand:'ACME'})}}
    </p>
    <p>
      {{t('authoring-phrase.by')}} <a href="https://newsapi.org" target="_blank">NewsAPI.org</a>
      {{t('footer.and')}} <a href="https://logo.dev" target="_blank">Logo.dev Logo API</a>
    </p>
  </div>
</div>
</template>

<style scoped>

</style>