<template>
  <!--Your App Starts Here -->
  <v-app id="inspire">
<Slide Y/>   
    <!--Header -->
   
    
    <AppBar/>

    <div class="mt-12 ml-n1" label="flat">
            <v-btn color="grey-darken-4" dark large>Categories</v-btn>
          </div>
    
    <Categoriesbtn/>
    <!--<v-app-bar color="yellow dark" dark fixed app>
      <v-toolbar-title>Freshmenu</v-toolbar-title>-->
       <!-- Component Example -->
    
      
      <Badge/>
    <!--</v-app-bar>-->
    
    <v-spacer> </v-spacer>
  
    <v-col cols="12" class="ml-6 my-n4">

      
    <Breadcrumb/>
    </v-col>

    <br>
    <v-container 
    class="mx-10">
    
    
    <v-col cols="12" 
    md="8" 
    sm="mx-n1 8"
    lg="8"
    >
    <v-img
      src="Penne Alfredo.jpeg" class="float-left">
    </v-img>
    </v-col>


    <v-row>
      <v-col class="mx-10" 
      lg="7"
      sm="6"
      md="12"
      >
         <h1>Penne Alfredo</h1> 
      </v-col>
    </v-row>
    
    <v-row>
      <v-col cols="12" class="mx-10"
      lg="7 my-n5"
      md="12"
      sm="12">
        <v-img src="Veg Icon.png" max-height="20" max-width="20" class="float-left my-1">
        </v-img> 
        <p class="font-weight-light mb-1 mx-6">Continental</p>
      </v-col>
    </v-row>    

<v-spacer> </v-spacer>
    
    <v-row>
      <v-col cols="12" class="mx-12"
      lg="6 my-4"
      md="6"
      sm="6">
    <h2><p class="font-weight-medium ml-1">₹ 199</p></h2>
      </v-col>
    </v-row>  


    <v-row>
      <v-col cols="12" class="mx-10"
      md="12"
      lg="6 my-n6">
    <v-btn rounded color="orange" dark>ADD + </v-btn>
    <h5><p class="font-weight-thin">Customisable</p></h5>
      </v-col>
    </v-row>  
  
    
    <v-row>
      <v-col cols="12" class="mx-10"
      md="12"
      >
    <h4><p class="font-weight-light mt-4">Penne pasta tossed in a luscious Alfredo sauce along with 
veggies, finished off with fresh parsley and grated 
cheese. 
Bring out the Kid-in-You!</p></h4>
      </v-col>
    </v-row>

<br>

    <v-row>
      <v-col class="mx-10"
      md="12"
      sm="6 my-n9">
    <h3><p class="font-weight-medium">Ingredients</p></h3>
    <h4><p class="font-weight-light mt-n2">Penne, Parmesan, Broccoli, Bell Pepper, Olive, Béchamel, 
    Nutmeg</p></h4>
    <br>
      </v-col>
      
      <v-col cols="12"
      md="12"
      sm="3 my-4 mx-10">
    <h3><p class="font-weight-medium ">Nutritional Values</p></h3>
    
      </v-col>
    </v-row>
    

    <v-row>
      <v-col  cols="12" 
      md="12 float-right"
      sm="6 my-n12 mx-7 float-left"
      lg="pr-9 float-left">
      
      <v-img src="Nut. values.png" max-width="400" max-height="400" class="float-right mx-7"></v-img>
      </v-col>
    </v-row>
      
      <ImageComponent/>
      
      <v-col cols="12" class="mx-1"
      md12>
    <h5><p class="font-weight-light">
The images shown do not directly compliment the primary Selected image
under similar contexts.</p></h5>
      </v-col>

     <v-row>
       <v-col>
     <v-img src="Facebook Icon.png" max-height="25" max-width="25" class="float-left rounded ml-5" ></v-img>
     <v-img src="Instagram icon.png" max-height="25" max-width="25" class="float-left mx-3" ></v-img>
     <v-img src="Twitter Icon.png" max-height="25" max-width="25" class="float-left rounded"></v-img>
    </v-col>
     
       <v-col>
     <v-img src="Golden Star.png" max-height="25" max-width="25" class="float-left ml-n2"></v-img>
     <v-img src="Golden Star.png" max-height="25" max-width="25" class="float-left"></v-img>
     <v-img src="Golden Star.png" max-height="25" max-width="25" class="float-left"></v-img>
     <v-img src="Golden Star.png" max-height="25" max-width="25" class="float-left"></v-img>
     <v-img src="Golden Star.png" max-height="25" max-width="25" class="float-left"></v-img>
       </v-col>
       
     </v-row>

     <br>
     <br>
     <br>
     <v-row>
     <v-flex class="mx-3"
      md12>
     <h1>Reviews</h1>
     </v-flex>
     </v-row>
     <p class="font-weight-regular">Total Reviews(1,024)</p>

     <br>
     <br>
     
     <v-img src="Profile logo 1.png" max-height="100" max-width="100" class="float-left"></v-img>

     <v-row>
      <v-col cols="12" class="mx-9" 
       md="12">
         <p class="font-weight-regular"> <h2>Harsh Soni</h2></p>
      </v-col>
    </v-row>
    
      <v-row>
      <v-flex class="mx-12 my-n2" 
       md12>
         <p class="font-weight-light mt-n5">91 Reviews &amp; 14 Followers</p>
      </v-flex>
      <v-flex class="mx-16"
      md12>
      <v-col cols="12 mt-n13">
     <v-img src="Golden Star.png" max-height="20" max-width="20" class="float-right"></v-img>
     <v-img src="Golden Star.png" max-height="20" max-width="20" class="float-right"></v-img>
     <v-img src="Golden Star.png" max-height="20" max-width="20" class="float-right"></v-img>
     <v-img src="Golden Star.png" max-height="20" max-width="20" class="float-right"></v-img>
     <v-img src="Golden Star.png" max-height="20" max-width="20" class="float-right"></v-img>
     </v-col>
      </v-flex>
      </v-row>

      <v-row>
      <v-flex class="mx-10" 
       md12>
         <p class="font-weight-light ml-1">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute 
irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      </v-flex>
      
    </v-row>

    <br>
     <br>
     
     <v-img src="Profile logo 2.png" max-height="100" max-width="100" class="float-left"></v-img>
    
    
    <v-row>
      <v-col cols="12" class="mx-9" 
       md="12">
         <p class="font-weight-regular"> <h2>Bani Kaur Gauri</h2></p>
      </v-col>
    </v-row>


    <v-row>
      <v-flex class="mx-12 my-n2" 
       md="12"
       sm="my-n3"
       >
         <p class="font-weight-light mt-n5">245 Reviews &amp; 47 Followers</p>
      </v-flex>
      
      <v-flex class="mx-16"
      md="12">
      <v-col cols="12 mt-n13" >
     <v-img src="Golden Star.png" max-height="20" max-width="20" class="float-right"></v-img>
     <v-img src="Golden Star.png" max-height="20" max-width="20" class="float-right"></v-img>
     <v-img src="Golden Star.png" max-height="20" max-width="20" class="float-right"></v-img>
     <v-img src="Golden Star.png" max-height="20" max-width="20" class="float-right"></v-img>
     <v-img src="Golden Star.png" max-height="20" max-width="20" class="float-right"></v-img>
     </v-col>
      </v-flex>
      </v-row>

      <v-row>
      <v-flex class="mx-10" 
       md12>
         <p class="font-weight-light ml-1">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute 
irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      </v-flex>
    
    </v-row>
      
  
  

    
    
    
      
    
    </v-container>
    <!-- Body -->
    <v-content light>
      <nuxt /> 
    </v-content>
    
    
    <Footer/>
    <!-- Footer -->
    

  </v-app>
</template>

<script>
export default {}
</script>

<style> 
  .white--text {
    border: 1px solid;
  }

   
   #inspire {
    
    background-color: white;
    color: black;
    
  }
</style>