<script setup lang="ts">
const { locale } = useI18n();
</script>

<template>
  <form>
    <select v-model="locale">
      <option value="en">English</option>
      <option value="ru">Русский</option>
    </select>
    <p>{{ $t('welcome') }}</p>
  </form>
</template>

<style scoped>

</style>