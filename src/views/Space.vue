<template>
  <div >
  <h3 class="red">Card Start</h3>

  <v-card
   class="mx-auto"
    outlined
    max-width="600"
  
  >
    <v-card-title>
     Twitter
    </v-card-title>

    <v-card-subtitle>
        Subtitle
    </v-card-subtitle>

 
     <v-card-text class="">
      "vue Rocks!"
    </v-card-text>


    <v-card-actions>
    <v-btn>Click Here</v-btn>
    <v-spacer></v-spacer>
      <v-btn>Click Here</v-btn>
    </v-card-actions>
  </v-card>


  <v-card
    class="mx-auto"
    color="#26c6da"
    dark
    max-width="400"
  >
    <v-card-title>
     Twitter
    </v-card-title>


    <v-card-title>
      <v-icon
        large
        left
      >
        mdi-twitter
      </v-icon>
      <span class="title font-weight-light">Twitter</span>
    </v-card-title>


    <v-card-subtitle>
        Subtitle
    </v-card-subtitle>

    <v-card-text class="headline font-weight-bold">
      "vue Rocks!"
    </v-card-text>
     <v-card-text class="">
      "vue Rocks!"
    </v-card-text>

    <v-card-actions>
      <v-list-item class="grow">
        <v-list-item-avatar color="grey darken-3">
          <v-img
            class="elevation-6"
            src="https://avataaars.io/?avatarStyle=Transparent&topType=ShortHairShortCurly&accessoriesType=Prescription02&hairColor=Black&facialHairType=Blank&clotheType=Hoodie&clotheColor=White&eyeType=Default&eyebrowType=DefaultNatural&mouthType=Default&skinColor=Light"
          ></v-img>
        </v-list-item-avatar>

        <v-list-item-content>
          <v-list-item-title>Evan You</v-list-item-title>
        </v-list-item-content>

        <v-row
          align="center"
          justify="end"
        >
          <v-icon class="mr-1">mdi-heart</v-icon>
          <span class="subheading mr-2">256</span>
          <span class="mr-1">·</span>
          <v-icon class="mr-1">mdi-share-variant</v-icon>
          <span class="subheading">45</span>
        </v-row>
      </v-list-item>
    </v-card-actions>

    <v-card-actions>
    <v-btn>Click Here</v-btn>
    <v-spacer></v-spacer>
      <v-btn>Click Here</v-btn>
    </v-card-actions>
  </v-card>



   <h3 class="red">Card End</h3>
   <hr/>
  <h4 class="green">Grid</h4>
  <v-card class="mt-5 mb-8">
    <v-card-text>

    <v-container>
    <v-row>
        <v-col cols="6">
          <v-card class="pa-2" outlined title>
          Column
          </v-card>
        </v-col>
     </v-row>
       <v-row no-gutters>
        <v-col cols="12">
          <v-card class="pa-2" outlined title>
          remove all space inside
          </v-card>
        </v-col>
     </v-row>
     <v-row>
        <v-col cols="12">
          <v-card class="pa-2" outlined title>
          Column
          </v-card>
        </v-col>
     </v-row>
      <v-row>
            <v-col cols="4">
                    <v-card class="pa-2" outlined title>
                    Column
                    </v-card>
            </v-col>
            <v-col cols="4">
                    <v-card class="pa-2" outlined title>
                    Column
                    </v-card>
            </v-col>
            <v-col cols="4">
                    <v-card class="pa-2" outlined title>
                    Column
                    </v-card>
            </v-col>
     </v-row>

     <v-row dense>
            <v-col cols="4">
                    <v-card class="pa-2" outlined title>
                    Column
                    </v-card>
            </v-col>
            <v-col cols="4">
                    <v-card class="pa-2" outlined title>
                    Column
                    </v-card>
            </v-col>
            <v-col cols="4">
                    <v-card class="pa-2" outlined title>
                    Column
                    </v-card>
            </v-col>
     </v-row>
    </v-container>

  </v-card-text>
  </v-card>

  <v-card class="mt-5 mb-8">
    <v-card-text>
    <v-container pa-0>
     <v-row>
        <v-col cols="12" sm="6" offset-sm="3">
          <v-card class="pa-2" outlined title>
          Column
          </v-card>
        </v-col>
     </v-row>
      <v-row  justify="space-between">
            <v-col cols="4">
                    <v-card class="pa-2" outlined title>
                    Column
                    </v-card>
            </v-col>
            <v-col cols="4">
                    <v-card class="pa-2" outlined title>
                    Column
                    </v-card>
            </v-col>
          
     </v-row>
    </v-container>
  </v-card-text>
  </v-card>
































 <h4 class="green"> End Grid</h4>

  <v-row>
   <h3 class="ml-sm-12">Spacing</h3>
  <!-- 
<h3 class="mx-auto">Spacing1</h3>
 <h3 class="ml-12">Spacing</h3>
<h3>Spacing</h3>
 <h3 class="ml-5">Spacing</h3>
<h3 class="ml-12">Spacing</h3>

<h3 class="ml-n17">Spacing</h3>

-->
  </v-row>
  <h3 class="display-3 red">Navigation Bar </h3>
  <v-card class="mt-5 mb-8">
    <v-card-text>
       <v-app-bar
      color="deep-purple accent-4"
      dense
      dark
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Page title</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
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
    </v-card-text>
 </v-card >

   <v-card class="mt-5 mb-8">
    <v-card-text>
       <v-toolbar
      color="deep-purple accent-4"
      dense
      dark
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Page title</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
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
    </v-toolbar>
    </v-card-text>
 </v-card >

 <h3 color="blue">End Navigation</h3>

  <h3 class="display-3 red">Buttons</h3>
<v-card class="mt-5 mb-8">
    <v-card-text>
      <v-row>
          <v-col cols="12">
            <v-btn small>Submit</v-btn>
          </v-col>
      </v-row>
       <v-row>
          <v-col cols="12">
            <v-btn large>Submit</v-btn>
          </v-col>
      </v-row>
       <v-row>
          <v-col cols="12">
            <v-btn large text>Submit</v-btn>
          </v-col>
      </v-row>
       <v-row>
          <v-col cols="12">
            <v-btn large outlined>Submit</v-btn>
          </v-col>
      </v-row>
      <v-row>
          <v-col cols="12">
            <v-btn large rounded>Submit</v-btn>
          </v-col>
      </v-row>
        <v-row>
          <v-col cols="12">
            <v-btn large depressed>Submit</v-btn>
          </v-col>
      </v-row>
       <v-row>
          <v-col cols="12">
            <v-btn large block>
            <v-icon left>mdi-pencil</v-icon>
            Submit</v-btn>
          </v-col>
      </v-row>
      <v-row>
          <v-col cols="12">
            <v-btn icon block>
            <v-icon left>mdi-pencil</v-icon>
            Submit</v-btn>
          </v-col>
      </v-row>
       <v-row>
          <v-col cols="12">
            <v-btn icon>
            <v-icon left>mdi-pencil</v-icon>
            </v-btn>
          </v-col>
      </v-row>
      <v-row>
          <v-col cols="12">
            <v-btn icon fab>
            <v-icon left>mdi-pencil</v-icon>
            </v-btn>
          </v-col>
      </v-row>

      <v-row>
          <v-col cols="12">
            <button class="elevation-24">
            Submit
            </button>
          </v-col>
      </v-row>

       <v-row>
          <v-col cols="12">
            <button class="elevation-2 py-2 px-4">
            Submit
            </button>
          </v-col>
      </v-row>

      <v-row>
          <v-col cols="12">
            <button v-ripple class="elevation-2 py-2 px-4">
            Submit
            </button>
          </v-col>
      </v-row>

       <v-row>
          <v-col cols="12">
          <v-btn tile outlined color="success">
          <v-icon left>mdi-pencil</v-icon>Edit
          </v-btn>
          </v-col>
      </v-row>




    </v-card-text>
 </v-card>


 
 </div>
</template>

<style scoped>
  .container{
    border: 1px solid green;
  }
  .row{
    border: 1px solid red;
  }
  .col{
      border: 1px solid blue;
  }
</style>
