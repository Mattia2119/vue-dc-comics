<template>

    <section class="comics">
        <div class="container">

            <div class="card">

            </div>

            <div class="card">

            </div>

            <div class="card">

            </div>

            <div class="card">

            </div>

            <div class="card">

            </div>

            <div class="card">

            </div>

            <div class="card">

            </div>

            <div class="card">

            </div>

            <div class="card">

            </div>

            <div class="card">

            </div>

            <div class="card">

            </div>

            <div class="card">

            </div>
            
            <div class="long-card">
                <a href="#">
                    <div class="current-series">
                            <h4>LOAD MORE</h4>
                    </div>
                </a>
            </div>
        </div>
    </section>
 
</template>


<script>
export default {
  name: 'MyMain',
}
</script>


<style scoped lang="scss">
@import "src/assets/style/variables.scss";

.comics {
    height: 600px;
    background-color: rgb(28, 28, 28);
    .container {
        height: 100%;
        width: 80%;
        margin: auto;
        .card {
            height: calc(80% / 2);
            width: calc(100% / 6);
            border: 1px solid white;
            float: left;
        }
        .long-card {
            height: 20%;
            width: 100%;
            float: left;
            display: flex;
            align-items: center;
            justify-content: center;
                a {
                    text-decoration: none;
                }
              .current-series {
                background-color: $primaryColor;
                width: 190px;
                padding: 10px;
                text-align: center;
                position: relative;
                top: 25px;
                    h4 {
                        color: white;
                        font-size: 12px;
                    }
            }
        }
    }
}


</style>
