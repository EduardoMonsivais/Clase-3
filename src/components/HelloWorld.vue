<template>
  <h1>Info Personal: {{ info }}</h1>
  <p>{{ Nombre }}</p>
<p>{{ Matricula }}</p>
<p>{{ Grupo }}</p>
</template>



<script>
export default {
  data () {
    return {
      info: "",
      Nombre: 'Jose Eduardo Monsivias Rodriguez',
      Matricula: '20989',
      Grupo: '5A'
      
    }
  }
}

</script>