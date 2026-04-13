<template>
  <div class="contenedor">
    <img src="./assets/logo.svg" alt="Vue logo" width="125" height="125" />
    <small>
      <h1>Hola mundo desde Vue. js 3</h1>
    </small>
    
    <h2>Contador: 0</h2>
    <button>+1</button>
    <button>-1</button>
    <button>Reiniciar</button>
  </div>
</template>

<style scoped>
.contenedor {
  text-align: center;
  background-color : #ddd;
}
small {
  Color:#666
}
h1 {
  font-weight: bolder;
}
h2 {
  font-size: 2.5 rem;
}
button {
  cursor: pointer;
  font-size: 1.5rem;
  margin: 0px 6px;

}
</style>
