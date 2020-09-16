<template>
  <!--Your App Starts Here -->
  <v-app id="inspire">
<Slide Y/>   
    <!--Header -->
    <v-app-bar color="yellow" dark fixed app>
      <v-toolbar-title>Aryan Katewa</v-toolbar-title>
       <!-- Component Example -->
      <Badge/>
    </v-app-bar>
<Breadcrumb/>
<Accordion/>
<Elevation/>
<Elevation/>
<Elevation/>
<Scroll/>
<Carousel/>
<Grids/>
<HorizontalCards/>
<CustomActions/>
<Loadingcard/>
<Modal/>
<Form/>
    <!-- Body -->
    <v-content light>
      <nuxt /> 
    </v-content>
    <Elevation/>
    <!-- Footer -->
    <v-footer color="indigo" app>
      <span class="white--text">&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>

  </v-app>
</template>

<script>
export default {}
</script>

<style> 
  .white--text {
    border: 1px solid;
  }

   /*
   #inspire {
    
    background-color: white;
    color: black;
    
  }*/
</style>