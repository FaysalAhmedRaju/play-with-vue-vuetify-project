<template>
   <v-app>
   <div>
      <v-app-bar>
            <v-toolbar-title>Awesome Shop</v-toolbar-title>

            <v-spacer></v-spacer>
             
              <span class="hidden-sm-and-up">
              <v-btn @click.stop="drawer = !drawer"><v-icon>mdi-view-dashboard</v-icon>
              </v-btn>
              </span>


            <v-toolbar-items class="hidden-xs-only">

                <v-btn to="/" text>
                <v-icon small left>mdi-home</v-icon>
                  Home
                </v-btn>

                 <v-btn to="store" text>
                <v-icon small left>mdi-shopping</v-icon>
                  Store
                </v-btn>

                 <v-btn to="cart" text>
                <v-icon small left>mdi-cart</v-icon>
                  Cart
                </v-btn>
            </v-toolbar-items>
      </v-app-bar>
      <v-navigation-drawer
        v-model="drawer"
        absolute
        temporary
        right
      >
       <v-list>
       <v-list-item
       v-for="item in items"
       :key="item.title"
       :to="item.link"
       link
       >
       <v-list-item-icon>
                          <v-icon small>
                          {{item.icon}}
                          </v-icon>
       </v-list-item-icon>
       <v-list-item-content>
                          <v-list-item-title> 
                          {{item.title}}
                          </v-list-item-title>
       </v-list-item-content>
      
       </v-list-item>

       </v-list>
      </v-navigation-drawer>
   </div>

   </v-app>
</template>

<script>
  export default {
    data(){

  return {
        drawer: false,
        items: [
          {title: 'Home', link: '/', icon: 'mdi-home'},
          {title: 'Store', link: 'store', icon: 'mdi-shopping'},
          {title: 'Cart', link: 'cart', icon: 'mdi-cart'}
        ]

    }  

    },
    }
</script>
