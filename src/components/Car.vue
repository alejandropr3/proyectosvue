<template>
  <h1>carro de vue</h1>
  <p>marca: {{marca}}</p>
  <p>color: {{color [1]}}</p>
  <p>recorrido: {{kilometraje}}</p>
  <p>precio: {{precio}}</p>
  {{mensaje.bienvenido}}

  <car2 />
     
</template>

<script>
import car2 from "./Car2.vue"

export default {
  data(){
    return{
        car2,
      marca: "ford",
      color: ["rojo","verde","azul","morado"],
      kilometraje: 0,
      precio: 200,
      mensaje:{
       bienvenido:"hola que tal que deseas",
       adios:"hasta luego un gusto"
      }

    }
  },
  components:{
    car2
  }
};
</script>

<style>

</style>