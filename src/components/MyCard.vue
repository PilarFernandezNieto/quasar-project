<template>
  <div class="q-pa-md row items-start q-gutter-md">
    <q-card class="my-card">
      <q-card-section horizontal>
        <div class="col-5 q-py-md q-pl-md">
          <q-img src="https://cdn.quasar.dev/img/parallax2.jpg" class="fit" />
        </div>
        <q-card-section>
          <div class="text-h6">Carrilleras</div>
          <div class="text-subtitle1 text-primary q-mt-sm">22 €</div>
          <div class="text-body2 q-mt-sm">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit.
          </div>
          <q-btn label="Guardar" color="primary" @click="saludo" class="q-mt-md" />
        </q-card-section>
      </q-card-section>
    </q-card>
  </div>
</template>

<script setup>
const saludo = () => {
  alert('Hola, mundo!')
}
</script>

<style lang="scss" scoped>
.my-card {
  width: 100%;
  border-radius: 5px;
  transition: box-shadow 0.3s ease;
}
q-img {
  height: 100%;
  width: 100%;
  object-fit: cover;
  border-radius: 5px;
}
.my-card:hover {
  box-shadow: 0 0 20px rgba(255, 255, 255, 0.5); /* sombra blanca */
}
</style>
