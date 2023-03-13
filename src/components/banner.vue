<template>
    <div class="banner d-flex flex-column justify-center align-items-center  ">
          
          <div class="intro typewriter">
            <p class="ma-0 pa-0">Introducting</p>
            <div class="">
              <h1 class="heading ma-0 pa-0 "> Jeancamlap's Website </h1>
            </div>
            <h2 class="secondary-text"> Website of a <span> Developer </span> and <span>Cyber security</span> passionate </h2>
          </div>
    </div>
</template>


<script>
export default {
    name:"banner"
}
</script>

<style>
@import '../assets/style.css';
</style>



<style lang="scss" >
     .banner {
        text-align: left;
        height:100vh;
        width:100vw;
        background-color: var(--main-bg-color);
        padding: 10%;
    }
    
    .intro{
       
        p {
            margin-left: 10px; 
            padding: 0;
            font-size: 1.5em ;
            font-weight: bold;
            color :var(--dark-accent) ;
        };

        span{
            color : var(--dark-accent);
        }

        .btn{
            color: var(--gray);
        }

      
        .secondary-text{
            color: var(--gray) ;
        }

        .heading {
            margin:0px; 
            padding: 0px;
            font-size: 4em ;
            color : var(--highlight-color);
        }

    }


</style>