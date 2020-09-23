<template>
  <v-container fluid
  v-row>
  <v-col
  v-for="i in 3"
  :key=i
  cols="12"
  md="4"
  >
  
  <v-card
    class="pa-md-4 pa-sm-6 pa-xs-3 mx-lg-auto"
    color="black"
    width="250px"
  >
    <v-card-text>
      Adjust screen size to see spacing changes
    </v-card-text>
  </v-card>
  </v-col>
  </v-row>
  </v-container>
</template>