<template>
  <div id="app">
    <h1>Ejemplo de Routing</h1>

    <router-link to="/router1" active-class="activo"><a>Enlace Router 1</a> | </router-link>
    <router-link to="/router2" active-class="activo"><a>Enlace Router 2</a> | </router-link>
    <router-link to="/router3" active-class="activo"><a>Enlace Router 3</a> | </router-link>
    <router-link to="/router4" active-class="activo"><a>Enlace Router 4</a></router-link>

    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
.activo, .activo a{
  color: red;
  background-color: rgba(0, 0, 0, 0.2);
}
</style>
