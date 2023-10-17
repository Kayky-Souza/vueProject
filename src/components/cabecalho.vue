<template>
    <header class="cabecalho">
    <ul class="lista">
      <div class="identificar_loja">
        <li class="logo"></li>
        <li class="nome_site"><a href="#">Nome do Site</a></li>
      </div>
      <li><a href="#">Ps4</a></li>
      <li><a href="#">Ps5</a></li>
      <li><a href="#">Xbox</a></li>
      <li><a href="#">Home</a></li>
      <li><a href="#">Fazer Login</a></li>
    </ul>
  </header>
</template>

<style scoped>
.cabecalho{
    background-color: black;
    width: 100%;
}
.lista{
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}
</style>

<script>
  export default{
    name: 'cabecalho'
  }
</script>