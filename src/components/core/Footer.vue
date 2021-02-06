<template>
  <v-footer
    class="py-4"
    color="#1E5F03"
    height="auto"
  >
    <v-container class="mx-auto">
      <v-row>
        
        
        <v-col cols="12" sm="3" >
          <v-img src="http://extrackt.in/public/uploads/logo/z4s2zAPsoayblW5GgImj4vetfCLe2PvKNjVoJ2Fg.png"
          width="200px"
          ></v-img>
          <h4>About Krushinaturals</h4>

          <p>
            PKrushiNaturals is an online
            fresh vegetables store
            ensuring that the best
            quality, naturally grown
            and fresh vegetables 
          </p>
        </v-col>


        <v-col cols="12" sm="3">
          <h4>Quick Links</h4>
            <v-list-item link>
              <v-list-item-content>
                <v-list-item-title >
                  <a
                href="#"
                class="text-decoration-none"
                 >Contact Us</a>
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-list-item link>
              <v-list-item-content>
                <v-list-item-title >
                  <a
                href="#"
                class="text-decoration-none"
                 >Contact Us</a>
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-list-item link>
              <v-list-item-content>
                <v-list-item-title >
                  <a
                href="#"
                class="text-decoration-none"
                 >Contact Us</a>
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>


          
        </v-col>

        <v-col cols="12" sm="3" >
           <h4>Legal</h4>

            <v-list-item link>
              <v-list-item-content>
                <v-list-item-title >
                  <a
                href="#"
                class="text-decoration-none"
                 >Contact Us</a>
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-list-item link>
              <v-list-item-content>
                <v-list-item-title >
                  <a
                href="#"
                class="text-decoration-none"
                 >Contact Us</a>
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>
            
        </v-col>

        <v-col cols="12" sm="3" >
          <h4>Get In Touch</h4>
          <p>
            Manjri Greens Phase-I Row House No
33, Maharashtra 412307
          </p>

          <p>+91 9021019593</p>

          <p>info@krushinaturals.co</p>

        </v-col>


        
      </v-row>
    </v-container>
  </v-footer>
</template>

<script>
  export default {
    name: 'CoreFooter',

    data: () => ({
      items: [
        {
          href: '#!',
          icon: 'mdi-twitter',
        },
        {
          href: '#!',
          icon: 'mdi-instagram',
        },
        {
          href: '#!',
          icon: 'mdi-facebook',
        },
        {
          href: '#!',
          icon: 'mdi-google-plus',
        },
        {
          href: '#!',
          icon: 'mdi-reddit',
        },
        {
          href: '#!',
          icon: 'mdi-discord',
        },
        {
          href: '#!',
          icon: 'mdi-pinterest',
        },
      ],
    }),
  }
</script>
