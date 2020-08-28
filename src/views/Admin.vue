<template>
  <div>
    <h1>PAGINA ADMINISTRADOR</h1>
    <h2>Bienvenido{{currentUser.email}}</h2>
  </div>
</template>
<script>
import {mapState} from 'vuex'
export default {

  computed:{
    ...mapState (['currentUser'])
  }
  
}
</script>