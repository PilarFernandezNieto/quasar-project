<template>
  <q-layout view="lHh Lpr lFf">
    <q-page-container class="dark">
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script setup></script>
<style lang="scss" scoped>
.dark {
  background-color: $dark;
}
</style>
