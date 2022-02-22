<template>
   <section class="options">
       <div class="container">

           <a href="">
           <div class="container-box">
                   <img src="../assets\img\buy-comics-digital-comics.png" alt=".">
                   <p>DIGITAL COMICS</p>
           </div>
           </a>

           <a href="">
           <div class="container-box">
                   <img src="../assets\img\buy-comics-merchandise.png" alt=".">
                   <p>DC MERCHANDISE</p>
           </div>
           </a>

           <a href="">
           <div class="container-box">
                   <img src="../assets\img\buy-comics-subscriptions.png" alt=".">
                   <p>SUBSCRIPTION</p>
           </div>
           </a>

           <a href="">
           <div class="container-box">
                   <img src="../assets\img\buy-comics-shop-locator.png" alt=".">
                   <p>COMIC SHOP LOCATOR</p>
           </div>
           </a>

           <a href="">
           <div class="container-box">
                   <img class="svg" src="../assets\img\buy-dc-power-visa.svg" alt=".">
                   <p>DC POWER VISA</p>
           </div>
           </a>

       </div>
   </section>
</template>



<script>
export default {
  name: 'MyBlueSection',
}
</script>


<style scoped lang="scss">

 @import "src/assets/style/variables.scss";

 .options {
     background-color: $primaryColor;
     height: 110px;

      .container {
           height: 100%;
           width: 80%;
           margin: auto;

           &::after {
                clear: both;
                display: block;
                content: ""; 
           }
                .container-box {
                    height: 100%;
                    width: calc(100% / 5);
                    float: left;
                    display: flex;
                    justify-content: center;
                    align-items: center;

                     &:hover {
                         p {
                             font-size: 16px;
                             transition: 0.5s;
                         }
                         img {
                                 height: 50px;
                                 transition: 0.5s;
                         }
                         img.svg {
                                 height: 40px;
                                 transition: 0.5s;
                         }
                     }
                     
                      img {
                          height: 40px;
                      }

                      img.svg {
                         height: 30px;
                      }

                      p {
                          font-size: 14px;
                          color: white;
                          margin-left: 20px;
                      }
                }
      }
 }
 
</style>