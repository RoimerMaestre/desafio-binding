<template>
  <TarjetaDatos />
</template>

<script>
import TarjetaDatos from "./components/TarjetaDatos.vue";

export default {
  name: "App",
  components: {
    TarjetaDatos,
  },
};
</script>

<style>
body{
display: flex;
justify-content: center;
margin-top: 200px;
}
</style>
