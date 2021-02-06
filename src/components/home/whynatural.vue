<template>
  <v-container-fluid>
     <base-card
        color="#8BC63E"
        class="pa-3"
        >
       
            <v-container class=" lighten-5">
                <base-subheading>WHY NATURAL FARMING ?</base-subheading>
                <v-row >
                    <v-col
                        cols="12"
                        sm="3"
                         v-for="user in users" :key="user.id"
                    >
                        <v-card
                        class="pa-2 "
                        outlined
                        tile
                        >
                        <v-h4 class="whynumber">{{user.id}}.</v-h4>
                        <v-img
                            v-if="user.src"
                            :src="require(`@/assets/articles/${user.src}`)"

                            width="220"
                            contain
                            class="darken-4 mycenterali myimgali"
                            >
                        </v-img>
                        <h2 class="text-center">{{user.textt}}</h2>
                        <h4 class="text-center">{{user.subtext}}</h4>
                        
                        </v-card>
                    </v-col>
                </v-row>
              
            </v-container>
    </base-card>
  </v-container-fluid>
</template>

<script>
  export default {
    name: 'whynatural',

    data(){
       return{
           users:[
               {id:1, textt:'BIJAMRITA', subtext:'Seed Treatment', src:'1.png' },
               {id:2, textt:'BIJAMRITA', subtext:'No Fertilisers No Pesticides', src:'2.png' },
               {id:3, textt:'BIJAMRITA', subtext:'Soil, Straw & Live', src:'3.png' },
               {id:4, textt:'BIJAMRITA', subtext:'Soil Moisture', src:'4.png' },
           ]
       }
    }
  }
</script>

<style scoped>
.v-sheet{
    background-color: transparent;
    border: none;
}
.v-card{
    background-color: transparent;
    border: none;
}
.mycenterali{
    margin: auto;
}

.myimgali{
    margin-top: -40px;
}

.whynumber{
    font-size: 20px;
    font-weight: bold;
    color: #B7DC8A;
    font-size: 50px;
}
.mytcolor{
    color: #FAFDFD;
}
</style>