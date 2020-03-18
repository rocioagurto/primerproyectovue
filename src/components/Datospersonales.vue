<template>
  <div class="box">
    <h1>Datos Personales</h1>
    <p>{{DatoNombre}} - {{ DatoRut }} - {{ DatoComuna }}</p>
  </div>
</template>



<script>
export default {
  name: "Personal",
  data() {
    return {
      DatoNombre: "ROCIO AGURTO LOPEZ",
      DatoRut: "16.382.420-5",
      DatoComuna : "Santiago"
    };
  }
};
</script>

<style scoped>

</style>