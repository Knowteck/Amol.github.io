<template>
  <v-container-fluid>
    <v-row class="no-gutters">
          <v-col 
          cols="12" 
          sm="6" 
          class="testimg_1">
            <v-div class="SPNFbox">
              <iframe width="100%" height="300"
src="https://www.youtube.com/embed/tgbNymZ7vqY?controls=0">
</iframe>
            </v-div>
          </v-col>

          <v-col 
          cols="12" 
          sm="6" 
          class="testimg_2">
          <v-row>

            <v-col 
            cols="12" 
            sm="3">
            
            </v-col>

            <v-col 
            cols="12" 
            sm="7">
              <base-subheading>TESTIMONIAL</base-subheading>
              <p>
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy text
                ever since the 1500s, when an unknown printer took a galley of
                type and scrambled it to make a type specimen book. It has
                survived not only five centuries, but also the leap into
                electronic typesetting, remaining essentially unchanged. It was
                popularised in the 1960s with the release of Letraset sheets
                containing Lorem Ipsum passages.
              </p>
            </v-col>
          </v-row>
          </v-col>
        </v-row>
  </v-container-fluid>
</template>



<script>
export default {
  name: "testi",
};
</script>


<style scoped>
.testimg_1 {
  background-color: #f4f9ec;
  background-position: right;
  width: 100%;
  height: 500px;
  position: relative;
}

.testimg_2 {
  width: 100%;
  height: 500px;
}

.SPNFbox {
     height: 300px;
    width: 100%;
    background-color: #f6e2c5;
    position: absolute;
    top: 110px;
    right: -100px;
}
.p2 {
  font-size: 20px;
}


@media screen and (max-width: 768px) {
  .SPNFbox {
  right:0px;
  width: 90%;
  }

}

</style>

