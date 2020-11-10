<template>
  <div class="container-wrapper-JinguLogo">
    <img :src="require('../assets/jingu-logo-512.png')"/>
  </div>
</template>

<script>
export default {
  name: 'vLogo',
  data () {
    return {
      nameText: 'Александр Быков'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container-wrapper-JinguLogo{
  width: 210px;
  height: 210px;
}
img{
  width: 210px;
  height: 210px;
  background: #191919;
  border-radius: 105px;
}
</style>
