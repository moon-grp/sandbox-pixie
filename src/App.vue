<template>
  <v-app>
    <v-app-bar
      app
      color="white"
      light
      elevate-on-scroll
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
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
   
   <v-row>
      <v-img
      
       :src="require('../assets/logo.svg')"
      aspect-ratio="1"
      class="grey lighten-2"
      max-width="100%"
      max-height="100vh"
    ></v-img>
   </v-row>

   <v-row>
      <v-toolbar>
      <v-toolbar-title>Title</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-toolbar-items>
        <v-btn text>Link 1</v-btn>
        <v-btn text>Link 2</v-btn>
        <v-btn text>Link 3</v-btn>
      </v-toolbar-items>

      <template v-if="$vuetify.breakpoint.smAndUp">
        <v-btn icon>
          <v-icon>mdi-export-variant</v-icon>
        </v-btn>
        <v-btn icon>
          <v-icon>mdi-delete-circle</v-icon>
        </v-btn>
        <v-btn icon>
          <v-icon>mdi-plus-circle</v-icon>
        </v-btn>
      </template>
    </v-toolbar>
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
</style>