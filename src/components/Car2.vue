<template>
<div class="vue3">
<h2>composition api vue 3 EXCLUSIVO DE VUE3</h2>
<p>marca: {{marca}}</p>
<p>tuning: {{color[2]}}</p>
<p>recorrido: {{kilometraje}}</p>
<p>valor: {{precio}}</p>
<p>mensaje cosesionario: {{mensaje.inicio}}</p>
  </div>
</template> 

<script>
export default {
setup(){
    const marca = "audi";
    const color = ["rojo","verde","gris"];
    const kilometraje = 0 ;
    const precio = 34300;
    const mensaje = {
        inicio:"hola audi",
        fin:"adios"
    }
    return{
        marca,
        color,
        kilometraje,
        precio,
        mensaje
    }
}
}
</script>

<style>
.vue3{
    width: 500px;
    background: rgb(51, 155, 110);
}


</style>