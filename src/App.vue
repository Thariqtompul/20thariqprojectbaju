<template>
  <v-app>
    <v-app-bar
      app
      color="purple"
      dark
    >

        <div>
        <v-col>
        <h1 v-resize-text class="font-weight-bold black--text text--darken-2">
          Project
        </h1>
        </v-col>
      </div>
      
      <v-spacer></v-spacer>
      
      <v-row
        align="center"
        justify="center"
      >
        <v-tabs
    fixed-tabs
    background-color="white"
    dark
  >
    <v-tab class="ml-1 black--text">
      List
    </v-tab>
    <v-tab class="ml-1 black--text">
     search
    </v-tab>
    <v-tab class="ml-1 black--text">
      cart
    </v-tab>
  </v-tabs>
        </v-row>
      
    <v-spacer></v-spacer>
        
        <v-hover
        open-delay="200"
      >
        <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
      depressed
      color="black"
    >
      LOGIN/REGISTER
    </v-btn>
    </v-hover>
    </v-app-bar>
    

    <v-main>

      <br />
      <br />
      <br />
      <br />
      <br />
      <br />
        <span>
        <v-col>
        <h1 v-resize-text class="display-1 font-weight-bold mb-3 text-center">
          STOCK KOSONG
          <br />
          MOHON MAAF!
        </h1>
        </v-col>
        <v-col>
        <h1 v-resize-text class="display-1 font-weight-regular mb-3 pl-2 text-center">
          Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
            sint. Velit officia consequat duis enim velit mollit. Exercitation
            veniam.
        </h1>
        </v-col>
          </span>

      
<div class="text-center">
        <v-btn
      class="ma-2"
      outlined
      rounded
      color="black"
    >
      LOGIN
    </v-btn>

        <body-2 class="font-weight-regular ml-2 mr-2 text-center">
          ATAU
        </body-2>


<v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
      depressed
      rounded
      color="green"
    >
      REGISTER
    </v-btn>
    </div>

        <br />
      <br />
      <br />
      <br />
      <br />
      <br />

          

        <v-col>
        <h1 class="display-1 font-weight-bold mb-3 pl-10 text-left">
        SIMPLE
          <br />
        </h1>
        </v-col>
        <v-col>
        <h1 class="display-1 font-weight-regular mb-3 pl-10 text-left">
          Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
            sint. Velit officia consequat duis enim velit mollit. Exercitation
            veniam.
        </h1>
        </v-col>

      <br />
      <br />

        <v-col>
        <h1 class="display-1 font-weight-bold mb-3 pr-10 text-right"
        style="margin-right=100">
        CEPAT
        </h1>
        </v-col>

        <v-col>
        <h1 class="display-1 font-weight-regular mb-3 pr-10 text-right">
          Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
            sint. Velit officia consequat duis enim velit mollit. Exercitation
            veniam.
        </h1>
        </v-col>
        
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />

        <v-col>
        <h1 class="display-1 font-weight-bold mb-3 pl-10 text-center">
        About Us
          <br />
        </h1>
        </v-col>
        <v-col>
        <h1 class=" font-weight-regular mb-3 text-center">
          Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
            sint. Velit officia consequat duis enim velit mollit. Exercitation
            veniam.
        </h1>
        </v-col>

        
    </v-main>
  
  <v-footer
color="grey"
    padless
  >
    <v-row
      justify="center"
      no-gutters
    >
      <v-col
        class="light-2 py-4 text-center white--text"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Muhammad Inwan At Thariq TI</strong>
      </v-col>
    </v-row>
</v-footer>
</v-app>
</template>

