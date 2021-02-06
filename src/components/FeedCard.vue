<template>
<v-container>
  <base-subheading>CATEGORY</base-subheading>
  <v-sheet
    class="mx-auto"
    max-width="100%"
  >

  
    <v-slide-group
      multiple
      show-arrows
    >
      <v-slide-item
        v-for="n in 20"
        :key="n"
        v-slot="{ active, toggle }"
      >
      
        <v-card
          class="mycardbox text-center"
          :input-value="active"
          active-class="purple white--text"
          depressed
          rounded
          @click="toggle"
        >
        <v-img
              src="https://i.ibb.co/mHjszTB/download.jpg"
              height="125"
              contain
              class=" darken-4"
            >
        </v-img>

        <v-card-title class="title text-center">
            <div style="margin: auto;"> 
                 <v-h3 > with contain</v-h3>
              </div>

         
        </v-card-title>
       
         <v-btn
          class="ma-2 text-center"
          outlined
          fab
          color="gray"
        >
        <v-icon>mdi-arrow-right</v-icon>
        </v-btn>

        </v-card>
      </v-slide-item>
    </v-slide-group>

    <v-row class="myspacer"></v-row>
    

    <v-slide-group
      multiple
      show-arrows
    >
      <v-slide-item
        v-for="n in 20"
        :key="n"
        v-slot="{ active, toggle }"
      >
      
        <v-card
          class="mycardbox text-center"
          :input-value="active"
          active-class="purple white--text"
          depressed
          rounded
          @click="toggle"
        >
        <v-img
              src="data:image/jpeg;base64,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"
              height="125"
              contain
              class=" darken-4"
            >
        </v-img>

        <v-card-title class="title text-center">
            <div style="margin: auto;"> 
                 <v-h3 > with contain</v-h3>
              </div>

         
        </v-card-title>
       
         <v-btn
          class="ma-2 text-center"
          outlined
          fab
          color="gray"
        >
        <v-icon>mdi-arrow-right</v-icon>
    </v-btn>

        </v-card>
      </v-slide-item>
    </v-slide-group>

  </v-sheet>
</v-container>
</template>

<script>
  export default {
    name: 'FeedCard',

  
  }
</script>

<script>
  export default {
    data: () => ({
      model: null,
    }),
  }
</script>

<style>
.v-image__image {
  transition: .3s linear;
}

.mycardbox{
  height: 250px;
  width: 250px;
  border: 1px solid #cac7ce!important;
  margin-right: 10px;
    margin-left: 5px;
    margin-top: 10px;
    margin-bottom: 10px;
}

.v-btn--fab.v-size--default {
    height: 45px;
    width: 45px;
}
.myspacer{
  height: 40px;
}

.v-sheet.v-card:not(.v-sheet--outlined){
  -webkit-box-shadow:none;
  box-shadow:none;
}

</style>
