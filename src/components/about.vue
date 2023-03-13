<template>
    <div id="about"> 
      <v-row>
          <v-col class="col-xs-12">
            <!-- add your personal bio paragraphs here in this column -->
            
            <h2> ABOUT ME</h2>
            <p>Hi, I am Jean-Camille LAPIERRE,</p>
            <p>They have completed their 1st year of DUT in Computer Science and their 3rd year of engineering school at ESISAR Valence.</p>
            <p>I have experience working as a freelancer on Fiverr, developing Python scripts, Java apps and websites using various technologies and frameworks.</p>
            <p>In 2021, I completed a development internship at Decalog and they hired me for two months, where I worked with Spring and Jenkins.</p>
            <p>I am interested in competitive mountain biking at the regional level.</p>
          </v-col>
          <v-col class="col-xs-12">
              <v-img src="../assets/velo.jpg" max-width="500px" contain >

              </v-img>
          </v-col>
      </v-row>
    </div>
</template>

<script>
export default {
    name : 'about'
}
</script>


<style lang="scss" scoped > 
    #about{
        padding-left: 10%;

       h2{  
           text-transform: uppercase;
           font-weight: bold;
           color:var(--accent-color);
           padding-top:15px;
        }
        p {
             padding-block: 10px;
             padding-right: 10px;
             font-weight: 400;
             color: var(--gray);
             font-size: 1.3em;
        }
    }

</style>