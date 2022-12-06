<template>
  <v-app>
    <v-app-bar
      absolute
      color="white"
      elevate-on-scroll
      scroll-target="#scrolling-techniques-7"
    >
      <v-app-bar-nav-icon class="hidden-md-and-up" @click="drawer = true"></v-app-bar-nav-icon>
      <nuxt-link to="/">
        <v-toolbar-title link>
          <img
            :src="require('../assets/img/Logo.png')"

            class="mt-2  ml-md-10 mr-4"
            lazy-load
          />
        </v-toolbar-title>
      </nuxt-link>

      <v-btn text class="text-capitalize hidden-sm-and-down">
       Home
      </v-btn>
      <v-btn text class="text-capitalize hidden-sm-and-down">
        Emotional Support
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn class="text-capitalize text-primary font-weight-bold hidden-sm-and-down" text>
       Login
      </v-btn>

      <v-btn class="text-capitalize mr-md-8 white--text ml-5 bg-primary rounded-lg font-weight-bold">
       Sign Up
      </v-btn>
    </v-app-bar>


    <v-main color="#FFFFFFF">
        <Nuxt />
    </v-main>

    <v-footer
      :absolute="!fixed"
      app
      color="bg-secondary"
      class="pt-3 pb-3"
    >
    <nuxt-link to="/">
        <v-toolbar-title link class="hidden-sm-and-down">
          <img
            :src="require('../assets/img/Logo-footer.png')"

            class="mt-2 ml-md-10 mr-4"
            lazy-load
          />
        </v-toolbar-title>
      </nuxt-link>
         <v-spacer class="hidden-sm-and-down"></v-spacer>
         <!--  -->

         <v-btn class="text-capitalize text-footer hidden-sm-and-down" text>
          Choose Listeners
        </v-btn>
         <v-btn class="text-capitalize text-footer hidden-sm-and-down" text>
          Emotional Support
        </v-btn>
         <v-btn class="text-capitalize text-footer hidden-sm-and-down" text>
          Terms and Conditions
        </v-btn>
         <v-btn class="text-capitalize text-footer mr-10 hidden-sm-and-down" text>
          Privacy Policy
        </v-btn>
        <v-list color="transparent" class="hidden-md-and-up">
          <v-list-item>
            <v-list-item-title class="text-footer">
              <img
            :src="require('../assets/img/Logo-footer.png')"

            class="mt-2 ml-md-10 mr-4"
            lazy-load
          />
            </v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-title class="text-footer"> Choose Listeners</v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-title class="text-footer"> Emotional Support</v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-title class="text-footer">Terms and Conditions</v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-title class="text-footer"> Privacy Policy</v-list-item-title>
          </v-list-item>
        </v-list>
    </v-footer>
    <v-navigation-drawer  v-model="drawer" absolute temporary>
      <v-list-item>

          <v-list-item-title class="text-h6">
            <img
            :src="require('../assets/img/Logo.png')"
            class="mt-2"
            lazy-load
            width="100"
          />
          </v-list-item-title>
        <v-list-item-icon class="mr-1 mt-4 mb-0" @click="drawer = false">
          <v-icon class=" font-weight-bold">mdi-close</v-icon>
        </v-list-item-icon>
      </v-list-item>

       <v-row>

        <v-col cols="12">
         <v-list>
          <v-list-item>
            <v-list-item-title>Home</v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-title>Emotional Support</v-list-item-title>
          </v-list-item>
         </v-list>
        </v-col>
        <v-col cols="12">
    <v-row>
      <v-col cols="11" class="mx-auto">
        <v-btn  block large class="text-capitalize white--text bg-primary rounded-lg font-weight-bold">
       Sign Up
      </v-btn>
      <v-btn block large class="text-capitalize text-primary font-weight-bold" text>
       Login
      </v-btn>
      </v-col>

    </v-row>
        </v-col>
       </v-row>


    </v-navigation-drawer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      title: 'Vuetify.js'
    }
  }
}
</script>
<style>
.text-primary{
  color:#F91E5A !important;
}
.text-footer{
  color:#939699 !important;
  font-size: 14px !important;
}
.bg-primary{
  background-color: #F91E5A !important;
}
.bg-secondary{
  background-color: #220660 !important;
}
</style>
