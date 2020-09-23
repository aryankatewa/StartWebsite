<template>
<v-container>
    <v-row
    no-gutters
    >
    <v-col
    v-for="i in 3"
    :key=i
    cols="12"
    md="4"
    >

      <v-card
        class="ma-6 pa-6"
      >
        <v-card-text>
          Centered
        </v-card-text>
      </v-card>

    </v-col>
    </v-row>

  <v-row
    no-gutters
    >
    <v-col
    v-for="j in 2"
    :key=j
    cols="12"
    md="6"
    >

      <v-card
        class="red lighten-2 pa-3"
      >
        <v-card-text>
          Centered
        </v-card-text>
      </v-card>

    </v-col>
    </v-row>
</v-container>
  </template>