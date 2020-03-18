<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Datospersonales></Datospersonales>
    <profesion></profesion>
    <Curso DatoCurso= "Curso FrontEnd G3 - Curso de aprendizaje semipresencial donde los contenidos teóricos los revisarás a tu propio ritmo, para que logres entender el lenguaje y las herramientas de manera segura y así poder avanzar sin ningún problema cada uno de los módulos logrando el objetivo de que entiendas y manejes el código sin ningún problema."></Curso>

  </div>
</template>

<script>

import Datospersonales from './components/Datospersonales.vue'
import Profesion from './components/Profesion.vue'
import Curso from './components/Curso.vue'

export default {
  name: 'App',
  components: {
    Datospersonales,
    Profesion,
    Curso
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
