<template>
  <div class="box">
    <h1>Curso</h1>
    <p>{{ DatoCurso }}</p>

  </div>
</template>


<script>
export default {
  name: "Curso",
  props: {
    DatoCurso: String
  },
};

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

p {
    width: 400px;
    margin: 0 auto;
    text-align: justify;
}
</style>
