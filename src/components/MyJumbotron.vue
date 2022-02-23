<template>
   <section class="jumbotron">
     <div class="container">
      <div class="current-series">
          <h4>CURRENT SERIES</h4>
      </div>
     </div>
   </section>
</template>


<script>
export default {
  name: 'MyJumbotron',
}
</script>


<style scoped lang="scss">

@import "src/assets/style/variables.scss";

  .jumbotron {
    height: 320px;
    background-image: url("../assets/img/jumbotron.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    .container {
      height: 100%;
      width: 80%;
      margin: auto;
      display: flex;
      align-items: flex-end;
       .current-series {
         background-color: $primaryColor;
         width: 190px;
         padding: 10px;
         text-align: center;
         box-shadow: 5px 5px 5px black;
         position: relative;
         top: 19.2px;
          h4 {
            color: white;
            font-size: 16px;
          }
       }
    }
  }

</style>
