<template>
  <header>
    <a href="#">
    <img src="../assets/img/dc-logo.png" alt="logo-dc">
    </a>

    <nav>
      <ul>
        
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
  
      </ul>
    </nav>

  </header>
</template>


<script>
export default {
  name: 'MyHeader',
}
</script>


<style scoped lang="scss">

@import "src/assets/style/variables.scss";

header {
  height: 80px;
  width: 80%;
  margin: auto;
  align-items: center;
  display: flex;
  justify-content: space-between;
     
     img{
        height: 60px;
     }

    ul {
      list-style: none;
      li{
        display: inline-block;
        font-size: 14px;
        font-weight: 600;
        margin: 10px;
      }
        a {
          text-decoration: none;
          color: rgba(71, 70, 70, 0.658);
          padding-top: 33px;
          padding-bottom: 29px;

            &:hover{
              color: $primaryColor;
              border-bottom: 4px solid $primaryColor;
            }
        }
    }
}

</style>
