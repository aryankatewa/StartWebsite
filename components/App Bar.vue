<template>
  <div>
    <v-app-bar
      color="white"
      dense
      light
    >
      <!--<v-app-bar-nav-icon></v-app-bar-nav-icon>-->

      <v-toolbar-title></v-toolbar-title>
      <v-img img src="FreshMenu.png" max-height="416" max-width="164"></v-img> 

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-cart</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-menu
        left
        bottom
      >
        <template v-slot:activator="{ on, attrs }">
          <v-btn
            icon
            v-bind="attrs"
            v-on="on"
          >
            <v-icon>mdi-dots-vertical</v-icon>
          </v-btn>
        </template>

        <v-list>
          <v-list-item
            v-for="n in 5"
            :key="n"
            @click="() => {}"
          >
            <v-list-item-title>Option {{ n }}</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-menu>
    </v-app-bar>
  </div>
</template>