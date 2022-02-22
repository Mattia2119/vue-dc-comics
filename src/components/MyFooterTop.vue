<template>

    <section class="info">

        <div class="container">

            <div class="left-side">

               <div class="col">
                   <ul>
                       <li><h3>DC COMICS</h3></li>
                       <li><a href="#">Characters</a></li>
                       <li><a href="#">Comics</a></li>                    
                       <li><a href="#">Movies</a></li>
                       <li><a href="#">Tv</a></li>                    
                       <li><a href="#">Games</a></li>
                       <li><a href="#">Videos</a></li>                  
                       <li><a href="#">News</a></li> 
                   </ul>
                   <ul>
                       <li><h3>SHOP</h3></li>
                       <li><a href="#">Shop DC</a></li>
                       <li><a href="#">Shop DC Collectibles</a></li>                  
                   </ul>
                </div>

               <div class="col">
                   <ul>
                       <li><h3>DC</h3></li>
                       <li><a href="#">Terms Of Use</a></li>
                       <li><a href="#">Privacy policy (New)</a></li>                    
                       <li><a href="#">Add Choices</a></li>
                       <li><a href="#">Advertising</a></li>                    
                       <li><a href="#">Jobs</a></li>
                       <li><a href="#">Subscriptions</a></li>                  
                       <li><a href="#">Talent Workshops</a></li> 
                       <li><a href="#">CPSC Certificates</a></li>                    
                       <li><a href="#">Ratings</a></li>
                       <li><a href="#">Shop Help</a></li>                  
                       <li><a href="#">Contact Us</a></li> 
                   </ul>
               </div>

               <div class="col">
                   <ul>
                   <li><h3>SITES</h3></li>
                       <li><a href="#">DC</a></li>
                       <li><a href="#">MAD Magazine</a></li>                    
                       <li><a href="#">DC Kids</a></li>
                       <li><a href="#">DC Universe</a></li>                    
                       <li><a href="#">DC Power Visa</a></li>
                    </ul>
               </div>
            </div>

            <div class="right-side"> 
              <!--Utile solo per il logo di background-->
            </div>

        </div>

    </section>
   
</template>


<script>
export default {
  name: 'MyFooterTop',
}
</script>


<style scoped lang="scss">
 .info {
       background-image: url('../assets/img/footer-bg.jpg');
       background-size: cover;
       height: 350px;
         .container {
             height: 100%;
             width: 80%;
             margin: auto;
               .left-side {
                   height: 100%;
                   width: 50%;
                   float: left;
                    .col {
                        height: 100%;
                        width: calc(100%/4);
                        float: left;
                        ul {
                            list-style: none;
                            padding-top: 30px;
                            li {
                                font-size: 12px;
                               padding: 3px;
                                   h3 {
                                       color: white;
                                       font-size: 20px;
                                       padding-bottom: 5px;
                                   }
                                
                                   a {
                                    color: rgba(126, 126, 126, 0.993);
                                    text-decoration: none;
                                        &:hover {
                                            color: white;
                                        }
                                }

                            }   
                        }
                    }
               }
               .right-side {
                   height: 100%;
                   width: 50%;
                   float: left;
                   background-image: url('../assets/img/dc-logo-bg.png');
                   background-repeat: no-repeat;
                   background-position: 100%;
                   background-size: 90%;
               }
              
         }
    }
</style>