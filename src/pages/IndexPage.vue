<template>
  <q-page class="q-pa-md column items-center">
    <MyCard v-for="i in 5" :key="i" />
  </q-page>
</template>
<script setup>
import MyCard from 'src/components/MyCard.vue'
</script>
<style lang="scss" scoped>
.q-page {
  width: 40%;
  margin: 0 auto;
}
</style>
