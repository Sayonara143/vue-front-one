<template>
  <div class="container-wrapper-NameText">{{nameText}}</div>
</template>

<script>
export default {
  name: 'vName',
  data () {
    return {
      nameText: 'Александр Быков'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container-wrapper-NameText{
  font-family: Roboto;
  font-style: normal;
  font-weight: 300;
  font-size: 114.894px;
  line-height: 135px;
  /* identical to box height */

  text-align: center;

  color: #000000;
}
@media screen and (max-width: 1444px) {
.container-wrapper-NameText{
  margin-top: 5vh;
  margin-bottom: 5vh;
  font-size: 40px;
  line-height: 47px;
  /* identical to box height */
  text-align: center;
  color: #000000;
}
}
</style>
