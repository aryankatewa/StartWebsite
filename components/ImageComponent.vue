<template>
  <v-container fluid>
    <v-row>
      <v-col cols="5" md="3">
        <v-img
          src="Dish 2nd Image.png" max-height="200" max-width="200">
          
        ></v-img>
      </v-col>

      <v-col cols="5" md="2">
        <v-img src="Dish 3rd Image.png" max-height="220" max-width="220">
          
        </v-img>
      </v-col>

      <v-col cols="5" md="2">
        <v-img src="Dish 4th Image.png" max-height="190" max-width="190">
          
        </v-img>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
  .bottom-gradient {
    background-image: linear-gradient(to top, rgba(0, 0, 0, 0.4) 0%, transparent 72px);
  }

  .repeating-gradient {
    background-image: repeating-linear-gradient(-45deg,
                        rgba(255,0,0,.25),
                        rgba(255,0,0,.25) 5px,
                        rgba(0,0,255,.25) 5px,
                        rgba(0,0,255,.25) 10px
                      );
  }
</style>
<style scoped>
  .bottom-gradient {
    background-image: linear-gradient(to top, rgba(0, 0, 0, 0.4) 0%, transparent 72px);
  }

  .repeating-gradient {
    background-image: repeating-linear-gradient(-45deg,
                        rgba(255,0,0,.25),
                        rgba(255,0,0,.25) 5px,
                        rgba(0,0,255,.25) 5px,
                        rgba(0,0,255,.25) 10px
                      );
  }
</style>