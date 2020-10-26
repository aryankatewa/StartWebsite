<template>
  <v-container fluid>
    <v-row>      
      <v-col cols="12" md="2" sm="6" class="mt-10 hidden-xs-only">   
        <v-responsive>
          <v-img :aspect-ratio="16/11" src="Dish 2nd Image.png"></v-img> 
        </v-responsive>             
      </v-col> 
        
              
      
      <v-col cols="12" md="2" sm="6" class="mx-16 mt-10 hidden-xs-only">   
        <v-card 
          tile            
          color="#546E7A">            
            <v-img :aspect-ratio="16/11" src="Dish 3rd Image.png"></v-img> 
        </v-card>               
      </v-col>
          
              
     
      <v-col cols="12" md="2" sm="6" class="mt-10 hidden-xs-only">   
        <v-card 
          tile            
          color="#546E7A">            
            <v-img :aspect-ratio="16/11" src="Dish 4th Image.png"></v-img>                     
        </v-card>               
      </v-col>             
    </v-row>                    
                  <div>
                    </div>        
                      
                    
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