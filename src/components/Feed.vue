<template>
  <v-container-fluid>
    <v-row>
      <v-col cols="12" class="bannerstyle">
        <slot />
      </v-col>

      <feed-card />
      
    </v-row>

    
  </v-container-fluid>
</template>

<script>
  // Utilities
  import {
    mapState,
  } from 'vuex'

  export default {
    name: 'Feed',

    components: {
      FeedCard: () => import('@/components/FeedCard'),
    },

  
    
  }
</script>

<style scoped>
.bannerstyle{
  padding: 0px;
}

</style>