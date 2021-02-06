<template>

  <v-container-fluid>
   
                <v-row 
                  class="no-gutters"
                >
                    <v-col
                        
                        cols="12"
                        sm="6"
                        class="FARMING_2"
                    >
                      <v-row>
                        <v-col
                          
                          cols="12"
                          sm="2"
                        >
                          
                        </v-col>

                        <v-col
                          
                          cols="12"
                          sm="9"
                        >
                          <base-subheading>SPNF</base-subheading>
                          <p>
                            Lorem Ipsum is simply dummy text
                             of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages.
                          </p>

                          <p>
                            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages.
                          </p>
                        </v-col>
                        
                      </v-row>
                    </v-col>

                    <v-col
                        cols="12"
                        sm="6"
                        class="FARMING_1"
                    >
                    <v-div
                      class="SPNFbox"
                    >
                    <p class="p2">Inspired by <br>
<b>Subhash Palekar Natural Farming <br>
(SPNF),</b> Our farming partners follow <br>
Natural & Ecological Farming Methods,</p>
                       
                    </v-div>
                    </v-col>
                </v-row>

  </v-container-fluid>
</template>



<script>
  export default {
    name: 'spnf',
  }
</script>


<style scoped>
.FARMING_1 {
   background-image: url('https://www.thehindu.com/sci-tech/agriculture/87sx5z/article30131510.ece/ALTERNATES/LANDSCAPE_1200/NEWS2FARMER');
  background-repeat: no-repeat;
  background-position: left;
  width: 100%;
  height:500px; 
  position: relative;
}

.FARMING_2 {
   
  width: 100%;
  height:500px; 
  background-color:#f4f9ec;
}

.SPNFbox{
  height: 200px!important;
    width: 400px!important;
    background-color: #f6e2c5;
    padding: 28px;
    bottom: 0px;
    position: absolute;
    opacity: 0.9;
}
.p2{
font-size: 20px;
}

@media screen and (max-width: 768px) {
  .SPNFbox {
  width: 100%!important;
  }

}

</style>

