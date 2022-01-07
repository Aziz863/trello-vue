<template>
  <footer>
    <span> Footer de la app de adidouh</span>
    <router-link class="btn-header" to="/">Mis paneles</router-link>
  </footer>
</template>

<script>
export default { 
    name: 'app-footer'
}
</script>

<style lang="scss" scoped>
footer {
  box-sizing: border-box;
  background-color: #cfd8dc;
  bottom: 0;
  left: 0;
  padding: 1rem;
  position: absolute;
  width: 100%;
}

</style>