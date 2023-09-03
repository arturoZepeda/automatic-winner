<script setup lang="ts">

</script>

<template>
  <div class="fichaInicial">
      <div class="justify-center space-x-12 space-y-36 shadow-lg bg-gray-600 w-full flex flex-row flex-wrap p-3 antialiased banner-personalizado columns-2">
        <div class="float-left items-center">
          <img class="rounded-lg shadow-lg imagen-principal" src="../assets/IMG_3165.jpg">
        </div>
        <div class="flex flex-row flex-wrap space-x-12 uppercase">
          <div class="w-full text-left text-white font-semibold relative pt-3 md:pt-0 align-content:center">
            <h1 class="text-4xl font-medium text-white">Arturo Zepeda, <span class="font-light text-white">30</span></h1>
            <p class="font-light text-white mt-3">CDMX, México</p>
            <p class="mt-8 text-white">Ingeniero en sistemas computacionales</p>
            <p class="mt-2 text-white">Universidad tecnologica de México</p>
          </div>
        </div>
      </div>
  </div>
</template>

<style scoped>
.banner-personalizado {
  background-repeat: no-repat;
  background-image: url(../assets/IMG_2997.jpeg);
  background-blend-mode: multiply;
  background-size: cover;
}
.fichaInicial{
  height: 50rem;
  align-self: center;
}
.imagen-principal{
  height: 20rem;
  width: 20rem;
  object-fit: cover;
  object-position: right;
  align-content: right;
}
</style>
