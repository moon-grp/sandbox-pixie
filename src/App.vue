<template>
  <v-app>
    <v-app-bar
      app
      color="#FFB300"
      light
      elevate-on-scroll
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
           :src="require('../src/assets/img2.png')"
          transition="scale-transition"
          width="40"
        />
        <span>PeeXoo</span>
      </div>

      <v-spacer></v-spacer>
      <v-btn
        class="custom-btn"
        rounded
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2 ">I am a Photographer</span>
      </v-btn>

     <v-btn
        class="custom-btn"
        rounded
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Explore Photos</span>
      
      </v-btn>

      <v-btn
        class="custom-btn"
        rounded
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Find Photographer</span>
      
      </v-btn>

      <v-btn
        class="custom-btn"
        rounded
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Find my Photos</span>
      
      </v-btn>

      <v-btn
        class="custom-btn"
        rounded
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Login or Register</span>
      </v-btn>
    </v-app-bar>
   
   <v-row >
      <v-img
      
       :src="require('@/assets/img1.jpg')"
      aspect-ratio="1"
      class="grey lighten-2"
      max-width="100%"
      max-height="100vh"
    ></v-img>
   </v-row>

    <v-row class="mt-5 ml-9">
      <v-col cols="8">
         <v-badge
      color="#FFB300"
      left
    >
      <template v-slot:badge>
         <v-icon dark>
          mdi-check
        </v-icon>
      </template>
      <span class="font-weight-black">
          Afroshots
        </span>
         </v-badge>
      </v-col>

      <v-col cols="4">
        <v-btn
        rounded
        color="#FFB300"
        >
        Message Photographer
        </v-btn>
          <v-btn
          class="ml-3"
        rounded
        color="#FFB300"
        >
        Book Now
        </v-btn>

      </v-col>
    </v-row>

   <v-row class="mt-8 mr-7 ml-7" max-height="100vh">
     <v-col>
       <v-date-picker v-model="picker"  header-color="#FFB300"></v-date-picker>
     </v-col>
     <v-col>
        <v-date-picker v-model="picker" header-color="#FFB300"></v-date-picker>
     </v-col>
     <v-col>
         <v-date-picker v-model="picker" header-color="#FFB300"></v-date-picker>
     </v-col>
   </v-row>
   <v-row max-height="100vh" class="mt-8  section">
     <v-col class="mr-7 ml-12">
       <v-row>
         <span class="font-weight-black">
           Quick Links
         </span>
         </v-row>
         <v-row>
         <span>
           find my Photos
         </span>
       </v-row>
       <v-row>
         <span>
           Find a Photographer
         </span>
       </v-row>
       <v-row>
         <span>
           Become a Photographer
         </span>
       </v-row>
     </v-col>

     <v-col>
       <v-row>
         <span class="font-weight-black">
           Company
         </span>
         </v-row>
         <v-row>
         <span>
           About Us
         </span>
       </v-row>
       <v-row>
         <span>
           FQAs
         </span>
       </v-row>
       <v-row>
         <span>
           Pricing
         </span>
       </v-row>
     </v-col>

      <v-col>
       <v-row>
         <span class="font-weight-black">
           Contact Us
         </span>
         </v-row>
         <v-row>
         <span>
           Aule GRA, Akure
         </span>
       </v-row>
       <v-row>
         <span>
           Ondo State
         </span>
       </v-row>
       <v-row>
         <span>
           +2348134043532
         </span>
       </v-row>
     </v-col>

   </v-row>

   <v-row>
      <v-footer>
    
    <div justify-center align-center>&copy; {{ new Date().getFullYear() }}</div> 
  </v-footer>
   </v-row>
  </v-app>
</template>

<script>


export default {
  name: 'App',

  components: {
    
  },

  data: () => ({
    //
  }),
};
</script>


<style >
  .custom-btn::before {
    color: transparent
}

.custom-btn:hover {
    background-color:#FFB300;
}

.section{
  background-color: #FFE083
}
</style>