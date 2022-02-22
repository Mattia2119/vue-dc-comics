<template>
 <footer>

    <section class="actions">
        <div class="container">

          <div class="left-side">
            <button id="sign-up">SIGN-UP NOW!</button>
          </div>

          <div class="right-side">
            <ul>
              <li><a href="#"><button>FOLLOW US</button></a></li>
              <li><a href="#"><img src="../assets\img\footer-facebook.png"></a></li>
              <li><a href="#"><img src="../assets\img\footer-twitter.png"></a></li>
              <li><a href="#"><img src="../assets\img\footer-youtube.png"></a></li>
              <li><a href="#"><img src="../assets\img\footer-pinterest.png"></a></li>
              <li><a href="#"><img src="../assets\img\footer-periscope.png"></a></li>
            </ul>
          </div>

        </div>
    </section>

 </footer>
   
</template>


<script>
export default {
  name: 'MyFooter',
}
</script>


<style scoped lang="scss">

@import "src/assets/style/variables.scss";
 
footer {

    .actions {
      background-color: rgb(48, 48, 48);
      height: calc(100vh - 625px);
        div.container {
          width: 80%;
          height: 100%;
          margin: auto;
             .left-side {
               width: 50%;
               height: 100%;
               float: left;
               display: flex;
               align-items: center;
                #sign-up {
                  background-color: transparent;
                  padding: 8px;
                  border: 1px solid $primaryColor;
                  color: white;
                  font-size: 15px;
                  cursor: pointer;
                }
             }
             .right-side {
                width: 50%;
                height: 100%;
                float: left;
                display: flex;
                align-items: center;
                justify-content: end;
                 ul {
                   list-style: none;
                   display: flex;
                   align-items: center;
                    li {
                      display: inline-block;
                      margin: 10px;
                        a img:hover {
                          filter: drop-shadow(0 0 0.75rem $primaryColor);
                        }
                        button {
                          background-color: transparent;
                          border: none;
                          color: $primaryColor;
                          font-weight: 600;
                          cursor: pointer;
                        }
                    }
                 }
             }
        }
    }
}

</style>
