<template>
  <div class="box">
    <h1>Profesion</h1>
    <p>{{ DatoProfesion }}</p>
  </div>
</template>

<script>
export default {
  name: "Profesion",
  data() {
    return {
      DatoProfesion: "Licenciada en Kinesiologia"
    };
  }
};

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
