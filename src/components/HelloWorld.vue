<template>
  <div class="container">
    <div class="container-wrapper">
      <vName/>
      <vLogo/>
    </div>
    <vRocket/>
  </div>
</template>

<script>
import vLogo from './vue-JinguLogo'
import vRocket from './vue-rocket'
import vName from './vue-NameText'
export default {
  name: 'HelloWorld',
  components: {
    vLogo,
    vRocket,
    vName
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .container{
    width: 100%;
    height: 100vh;
    display: flex;
    align-items: center;
    flex-direction: column;
  }
  .container-wrapper{
    margin-top: 145px;
    width: 75%;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap-reverse;
    justify-content: space-between;
  }
@media screen and (max-width: 1444px) {
  .container{
    padding-top: 10vh;
    padding-bottom: 10vh;
    justify-content: center;

    /* justify-content: space-between; */
  }
  .container-wrapper{
    margin: 0;
    align-items: center;
    flex-direction: column-reverse;
   }
}
</style>
