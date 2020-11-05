<template>
  <!--Your App Starts Here -->
  <v-app id="inspire">
<Slide Y/>   
    <!--Header -->
   
    
    <!--Navigation Bar added with logo png and icons from vuetify library-->
    <AppBar/>

    <div class="mt-12 ml-n1" label="flat">
            <v-btn color="black" dark large>Categories</v-btn>
          </div>
    
    
   
    <!--<v-app-bar color="yellow dark" dark fixed app>
      <v-toolbar-title>Freshmenu</v-toolbar-title>-->
       <!-- Component Example -->
    
      
      <Badge/>
    <!--</v-app-bar>-->
    
    <v-spacer> </v-spacer>
  
    <v-col 
      cols="12" 
        class="ml-6 my-n4">
          <Breadcrumb/>
    </v-col>

    <br>
    <v-container 
    >
    
  
    <!--The primary and prominent dish added and made responsive
    Used aspect ratio to maintain the size and content of the images
    Used float-left to maintain the image and tex in aligned rows(as shown in XD Design-->
    <v-col wrap="12" justify="left" aspect-ratio="16/9"   >
      <v-img
        src="Penne Alfredo.jpeg" class="float-left xs-mx-4">
      </v-img>
    </v-col>
  
<!--Made the text in h1 to give prominence to the name of the dish
Made it responsive to different viewport sizes-->
    <v-row>
      <v-col class="mx-10" 
       lg="7"
       sm="6"
       md="12"
      >
         <h1>Penne Alfredo</h1> 
      </v-col>
    </v-row>
    
<!--Added a png image of an Vegetrian Icon
Kept it in the same row as "Continental" 
Added dimensions to the icon to maintain the visibility of the icon in different viewport sizes
Made the icon and "Continental" simeltaneously responsive-->    
    <v-row>
      <v-col cols="12" class="mx-10"
        lg="7 my-n5"
        md="12"
        sm="12">
          <v-img src="Veg Icon.png" max-height="20" max-width="20" class="float-left my-1"></v-img> 
        <p class="font-weight-light mb-1 mx-6">Continental</p>
      </v-col>
    </v-row>    

<v-spacer> </v-spacer>
    
<!--Added a price of the Dish
Used h2 for prominence in the text-->    
    <v-row>
      <v-col cols="12" 
        class="mx-10"
        lg="6"
        md="6 "
        sm="6"
        xs="12">
          <h2><p class="font-weight-medium ml-1">₹ 199</p></h2>
      </v-col>
    </v-row>  


    <!-- Button Component with clickable functionality
    Orange color to maintain the them colors of the brand
    Rounded property to match the roundedness of design in XD-->
    <v-row>
      <v-col cols="12" class="mx-10"
        md="12"
        lg="6 my-n6"
        sm="4">
          <v-btn rounded color="orange" dark>ADD + </v-btn>
            <h5><p class="font-weight-thin">Customisable</p></h5>
      </v-col>
    </v-row> 
  
    
<!--Added a description of the Dish 
kept the margin "10" from the border 
-->    
    <v-row>
      <v-col  class="mx-10 "
        md="12" 
        sm="12"
      >
        <h4><p class="font-weight-light mt-4">Penne pasta tossed in a luscious Alfredo sauce along with 
        veggies, finished off with fresh parsley and grated 
        cheese. 
        Bring out the Kid-in-You!</p>
        </h4>
      </v-col>
    </v-row>

<br>

<!--Ingredients Text 
used two font classes h3 and h4 to establish a sense of visual heirarchy 
-->
    <v-row>
      <v-col class="mx-10"
        md="12"
        sm="6 my-n9">
          <h3><p class="font-weight-medium">Ingredients</p></h3>
          <h4><p class="font-weight-light mt-n2">Penne, Parmesan, Broccoli, Bell Pepper, Olive, Béchamel, Nutmeg</p></h4>
     </v-col>
    </v-row>

<!--The heading Nutritional Values
Justified it to the left 
For different viewport sizes
 -->      
      <v-row justify="left">
      <v-col
       cols="12"
        md="12"
        sm="6 ml-9 mt-7">
          <h3><p class="font-weight-medium">Nutritional Values</p></h3>
    
      </v-col>
      </v-row>
    

<!--Added a png designed in XD for the nutritional values
added aspect ration for maintaining the dimensions of the png
Aligned for different viewport sizes-->     
    <v-row justify="center" aspect-ratio="16/9">
      <v-col   class="mx-xs-2"
        md="6 mr-5"
        sm="3 mt-n10"
        lg="12 mx-15"
        
        >
          <v-img src="Nut. values.png" max-width="400" max-height="400" class="float-right mx-7"></v-img>
      </v-col>
    </v-row>
      
      <ImageComponent/>
      
<!--A cautios sign that signifies some images may be out of the context in terms of the photography
Justified it in center to match the previous set of 3 images in the design
 -->    
    <v-row justify="center">  
      <v-col cols="12" class="ml-lg-16"
      
      xs="12 mx-10">
        <h5><p class="font-weight-light"> <font align="left"> 
        The images shown do not directly compliment the primary selected image
        under similar contexts.</font> </p></h5>
      </v-col>
    </v-row>

<!-- Added icons for social media
specified height and width to maintain the visibility of th icons
added a rounded class
used float class to keep it aligned with the primary image-->     
     <v-row>
       <v-col>
          <v-img src="Facebook Icon.png" max-height="25" max-width="25" class="float-left rounded ml-5" ></v-img>
          <v-img src="Instagram icon.png" max-height="25" max-width="25" class="float-left mx-3" ></v-img>
          <v-img src="Twitter Icon.png" max-height="25" max-width="25" class="float-left rounded"></v-img>
       </v-col>
     
       <v-col>
          <v-img src="Golden Star.png" max-height="25" max-width="25" class="float-left ml-n2 "></v-img>
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
       
<!--The heading Reviews
Justified it to the left 
For different viewport sizes
 -->         
       <v-flex class="mx-7"
        md12>
          <h1>Reviews</h1>
       </v-flex>
     </v-row>
       <p class="font-weight-regular mx-4">Total Reviews(1,024)</p>

     <br>
     <br>
     
<!-- Added a profile icon to compliment the review section 
specified dimensions in the logo-->     
     <v-img src="Profile logo 1.png" max-height="100" max-width="100" class="float-left"></v-img>

<!--Used font class for displaying the name aligned to the profile logo
-->     
     <v-row>
      <v-col class="mx-9" 
       md="12">
        <font family="font-weight-regular"> <h2> Harsh Soni</h2></font>
      </v-col>
     </v-row>
    
<!--Added the numbers of reviews and followers 
 -->      
      <v-row>
      <v-flex class="mx-12 my-n2" 
         md="12"
         sm="my-n3"
       >
         <p class="font-weight-light mt-1">91 Reviews &amp; 15 Followers</p>
      </v-flex>

<!--Added a ratings system for functionality and liking the comments 
float right to maintain the design language portrayed in XD -->      
       <v-flex class="mx-16 mt-6"
         md="12">
          <v-col cols="12 mt-n13">
          <v-rating  
            color="yellow" aspect-ratio="16/7"  class="float-right" half-increments length="5"  value="4">
          </v-rating>
        </v-col>
       </v-flex>
    </v-row>

<!--Used p to maintain the size of the paragraph in different viewport sizes
Flex class to enhance the responsiveness of th text -->     
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
     
<!-- Added a profile icon to compliment the review section 
specified dimensions in the logo--> 
     <v-img src="Profile logo 2.png" max-height="100" max-width="100" class="float-left"></v-img>
    
    
<!--Used font class for displaying the name aligned to the profile logo
-->         
    <v-row>
      <v-col cols="12" class="mx-9" 
        md="12">
         <font family="font-weight-regular"> <h2>Bani Kaur Gauri</h2></font>
      </v-col>
    </v-row>

<!--Added a ratings system for functionality and liking the comments 
float right to maintain the design language portrayed in XD 
aspect ratio to maintain the user funtionality and visibility-->  
    <v-row>
      <v-flex class="mx-12 my-n2" 
         md="12"
         sm="my-n3"
       >
         <p class="font-weight-light mt-1">245 Reviews &amp; 47 Followers</p>
      </v-flex>
      
       <v-flex class="mx-16 mt-6"
         md="12">
          <v-col cols="12 mt-n13">
          <v-rating  
            color="yellow" aspect-ratio="16/7"  class="float-right" half-increments length="5"  value="4">
          </v-rating>
        </v-col>
       </v-flex>
    </v-row>

<!--Used p to maintain the size of the paragraph in different viewport sizes
Flex class to enhance the responsiveness of th text -->  
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
    
    
    <v-row>
      <Footer/>
    </v-row>
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