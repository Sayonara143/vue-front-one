<template>
  <div class="container-Emoji">
    <p class="container-Emoji-rocket" role="img" aria-label="rocket">🚀</p>
  </div>
</template>

<script>
export default {
  name: 'vRocket'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
p{
  margin:0;
  padding: 0;
}
@keyframes rocket-jump {
  10%{transform: translateY(-3px);}
  20%{transform: translateY(-6px);}
  30%{transform: translateY(-9px);}
  40%{transform: translateY(-12px);}
  50%{transform: translateY(-15px);}
  60%{transform: translateY(-12px);}
  70%{transform: translateY(-9px);}
  80%{transform: translateY(-6px);}
  90%{transform: translateY(-3px);}
  100%{transform: translateY(0px);}
}
.container-Emoji{
  width: 75%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.container-Emoji-rocket{
  width: 205px;
  height: 205px;
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 205px;
  line-height: 240px;
  animation: rocket-jump  1s infinite;

  color: #000000;
}
@media screen and (max-width: 1444px) {
  .container-Emoji{
    display: flex;
    justify-content: center;
  }
  .container-Emoji-rocket{
    width: 80px;
    height: 80px;
    font-size: 80px;
    line-height: 94px;
    color: #000000;
  }
}
</style>
