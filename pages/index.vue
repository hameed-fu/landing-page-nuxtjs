<template>

  <v-container-fluid>
    <div style="background-color:#F4F2F7;">


      <v-row class="mx-md-8 my-6 py-6">
        <v-col cols="12" sm="12" md="6" lg="6" class="mt-6 pt-6">
          <div class="mt-5 mx-5" style="height:100%">
            <h3 style="font-weight: 700;font-size: 33px;color: #220660;">Meet Our Professional Listeners and Start
              Receiving Emotional Support in Just Seconds!</h3>
            <p class="" style="color: #272D33;">Do you have problems and need emotional support? Our experienced and
              professional listeners are waiting for you to help you deal with your problems. <br>
              So, choose your listener now and start online support.</p>
            <v-btn dark class="text-capitalize rounded-lg hidden-sm-and-down" elevation="0"
              style="background: #F91E5A;">Choose Listener</v-btn>
            <v-btn text class="text-capitalize hidden-sm-and-down" style="color: #F91E5A;">See How It Works</v-btn>
            <v-btn block dark class="text-capitalize rounded-lg hidden-md-and-up" elevation="0"
              style="background: #F91E5A;">Choose Listener</v-btn>
            <v-btn block text class="text-capitalize hidden-md-and-up" style="color: #F91E5A;">See How It Works</v-btn>
          </div>
        </v-col>
        <v-col class="ps-7 mt-5" cols="12" sm="6" md="6" lg="6">
          <img src="../assets/img/one.PNG" alt="" width="100%" />
        </v-col>
      </v-row>

      <v-row class="mx-6 px-6 my-6 py-6">
        <v-col cols="12">
          <h2 class="text-center" style="color: #F91E5A;">
            How Does It Work?
          </h2>
          <p class="text-center" style="color: #272D33;">In just a few steps, you're ready to connect with our
            listeners.</p>
        </v-col>
        <v-col cols="12" sm="6" md="4" lg="4">
          <h3 class="text-center" style="color: #272D33;">Step 1</h3>
          <p class="text-center" style="color: #272D33;">Enter your e-mail</p>
          <p class="text-center"><v-avatar size="200"><img src="../assets/img/Group8.png" width=""
                alt=""></v-avatar> </p>
        </v-col>
        <v-col cols="12" sm="6" md="4" lg="4" class="">
          <h3 class="text-center" style="color: #272D33;">Step 2</h3>
          <p class="text-center" style="color: #272D33;">Set your password</p>
          <p class="text-center"><v-avatar size="200"><img src="../assets/img/Group 9.png" width=""
                alt=""></v-avatar> </p>
        </v-col>
        <v-col cols="12" sm="6" md="4" lg="4">
          <h3 class="text-center" style="color: #272D33;">Step 3</h3>
          <p class="text-center" style="color: #272D33;">Set your nickname</p>
          <p class="text-center"><v-avatar size="200"><img src="../assets/img/Group 10.png" width=""
                alt=""></v-avatar> </p>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="10" class="mx-auto mb-6 pb-6">
          <v-row class="" style="background-color:white">
            <v-col cols="10" class="mx-auto mb-4 mt-6">
              <h3 class="text-md-center font-weight-regular mb-3"><span class="font-weight-bold">Do you want to connect
                  anonymously? </span> Then we have a suitable option for you, too.
                Just enter your e-mail address and confirm. Now you are ready to meet the listeners.</h3>
              <v-row no-gutters>
                <v-col cols="12" sm="12" md="6" lg="6" offset="0" offset-md="2" offset-lg="2">
                  <v-text-field outlined dense placeholder="Enter your e-mail address"></v-text-field>
                </v-col>
                <v-col cols="12" sm="12" md="4" lg="4">
                  <v-btn dark class="text-capitalize ml-3 hidden-sm-and-down" height="39" elevation="0"
                    color="#F91E5A">Submit</v-btn>
                  <v-btn dark class="text-capitalize hidden-md-and-up" height="39" elevation="0" block
                    color="#F91E5A">Submit</v-btn>
                </v-col>

              </v-row>
            </v-col>
          </v-row>
        </v-col>
      </v-row>

      <v-row class="mx-3 mx-md-6">
        <v-col cols="12">
          <h2 class="text-center" style="color: #F91E5A;">Why should I choose MENTALSO?</h2>
        </v-col>
        <v-col cols="12" sm="12" md="5" lg="6" class=" px-md-3 mt-md-10">
          <p><span style="color: #F91E5A;font-weight:700">MENTALSO</span> offers options to give you emotional support
            and make you feel good in your difficult times. Unlike many online support platforms, <span
              style="color: #F91E5A;font-weight:700">MENTALSO</span> has mental health professionals who have completed
            their licenses in Turkey. Our professional listeners are ready to listen and solve your problems and provide
            online support to make you feel better.</p>
          <p>If you want to benefit from our free emotional support service, you can chat with our professional
            listeners for 30 minutes for free once a week. If you want to make a video or audio call and get emotional
            support, you can feel better for <span style="ccolor: #272D33;font-weight:700">$19 for 30 minutes.</span>
          </p>
          <p>Our professional listeners are waiting for you! Choose the option you want and join us. <span
              style="color: #F91E5A;font-weight:700">MENTALSO</span> is with you to take a step towards happiness!</p>

        </v-col>
        <v-col cols="12" sm="12" md="6" lg="5" class="pl-md-16 ml-md-15">
          <img width="90%" src="../assets/img/Group 12.png" alt="">
        </v-col>

      </v-row>


      <v-row class="my-6 hidden-sm-and-down">
        <v-col cols="12">
          <h2 class="text-center mx-3" style="color: #F91E5A;">Select One of Our Experts Below and <br> Start the
            Healing Process</h2>
          <v-card class="mx-auto rounded-lg my-4" max-width="800" outlined>
            <v-list-item three-line>
              <img height="95" src="../assets/img/cart1.png">
              <!-- <v-avatar color="grey" size="95">
                <v-img src="../assets/img/cart1.png"></v-img>
              </v-avatar> -->
              <v-list-item-content>

                <v-list-item-title style="color: #272D33;" class="text-h6 mb-1 mt-4 ml-3">
                  Andrea Piacquadio <span>
                    <v-icon small class="pb-1" color="orange">mdi-star-outline</v-icon>
                    <v-icon small class="pb-1" color="orange">mdi-star-outline</v-icon>
                    <v-icon small class="pb-1" color="orange">mdi-star-outline</v-icon>
                    <v-icon small class="pb-1" color="orange">mdi-star-outline</v-icon>
                    <v-icon small class="pb-1" color="orange">mdi-star-outline</v-icon>
                    <span class="mb-n4" style="color: #939699;font-size:14px">
                      4,7 of 5 (152 reviews)
                    </span>
                  </span>

                </v-list-item-title>
                <v-list-item-subtitle class="ml-3 caption" style="color: #272D33;">This will be listener’s biography.
                  Ex: Lorem ipsum dolor sit amet consectetur. Varius malesuada est augue tellus nulla cursus. Lorem
                  ipsum dolor sit amet consectetur. Varius malesuada est augue tellus nulla
                  cursus.</v-list-item-subtitle>
                <v-card-actions>
                  <p style="color: #220660;font-weight: 700;">$19 <span class="caption">per session</span></p>
                  <v-spacer></v-spacer>
                  <v-btn small outlined dark class=" text-capitalize rounded-lg" style="background:#220660;">
                    Make Appointment
                  </v-btn>
                  <v-btn small dark class="text-capitalize rounded-lg" style="background: #F91E5A;">Call Now</v-btn>
                </v-card-actions>
              </v-list-item-content>


            </v-list-item>


          </v-card>
          <v-card class="mx-auto rounded-lg my-4" max-width="800" outlined>
            <v-list-item three-line>
              <img height="95" src="../assets/img/cart2.png">
              <v-list-item-content>

                <v-list-item-title style="color: #272D33;" class="text-h6 mb-1 mt-4 ml-3">
                  Andrea Piacquadio <span>
                    <v-icon small class="pb-1" color="orange">mdi-star-outline</v-icon>
                    <v-icon small class="pb-1" color="orange">mdi-star-outline</v-icon>
                    <v-icon small class="pb-1" color="orange">mdi-star-outline</v-icon>
                    <v-icon small class="pb-1" color="orange">mdi-star-outline</v-icon>
                    <v-icon small class="pb-1" color="orange">mdi-star-outline</v-icon>
                    <span class="mb-n4" style="color: #939699;font-size:14px">
                      4,7 of 5 (152 reviews)
                    </span>
                  </span>

                </v-list-item-title>
                <v-list-item-subtitle class="ml-3 caption" style="color: #272D33;">This will be listener’s biography.
                  Ex: Lorem ipsum dolor sit amet consectetur. Varius malesuada est augue tellus nulla cursus. Lorem
                  ipsum dolor sit amet consectetur. Varius malesuada est augue tellus nulla
                  cursus.</v-list-item-subtitle>
                <v-card-actions>
                  <p style="color: #220660;font-weight: 700;">$19 <span class="caption">per session</span></p>
                  <v-spacer></v-spacer>
                  <v-btn small outlined dark class=" text-capitalize rounded-lg" style="background:#220660;">
                    Make Appointment
                  </v-btn>
                  <v-btn small dark class="text-capitalize rounded-lg" style="background: #F91E5A;">Call Now</v-btn>
                </v-card-actions>
              </v-list-item-content>


            </v-list-item>


          </v-card>
         
        </v-col>
      </v-row>

      <v-row class="hidden-md-and-up">
        <h2 class="text-center mx-0 px-6" style="color: #F91E5A;">Select One of Our <br> Experts Below and Start the
          Healing Process</h2>
        <v-card class="mx-auto my-6 mx-auto mb-4 mt-6 col col-10" max-width="374">
          <v-card-title class="justify-center">
            <img height="150" src="../assets/img/cart1.png">
          </v-card-title>

          <v-card-title class="justify-center">Andrea Piacquadio</v-card-title>

          <v-card-text class="text-center">


            <v-rating :value="4.5" color="amber" dense style="display:inline" half-increments readonly
              size="14"></v-rating>

            <span class="grey--text mx-2">
              4.5 of 15 (413 reviews)
            </span>
          </v-card-text>

          <v-card-title class="body-2 mx-6 mt-0 pt-0">This will be listener’s biography. Ex: Lorem ipsum dolor sit amet
            consectetur. Varius malesuada est augue tellus nulla cursus. Lorem ipsum dolor sit amet consectetur. Varius
            malesuada est augue tellus nulla cursus.</v-card-title>
          <p style="color: #220660;font-weight:600" class="mx-6 px-6 text-center">$19 <span class="caption">per
              session</span></p>

          <div class="mx-5">
            <v-btn color="elevation-0" block dark style="background: #220660" class="rounded-lg">
              Make Appoinment
            </v-btn>
            <v-btn elevation="0" dark class="rounded-lg my-3 " block style="background: #F91E5A;">Call Now</v-btn>
          </div>


        </v-card>
        <v-card class="mx-auto mx-auto mb-4 mt-6 col col-10 px-4 mt-2" max-width="374">
          <v-card-title class="justify-center">
            <!-- <v-avatar size="88"> -->
              <img height="150" src="../assets/img/cart2.png">
            <!-- </v-avatar> -->
          </v-card-title>

          <v-card-title class="justify-center">Maria Cabello</v-card-title>

          <v-card-text class="text-center">


            <v-rating :value="4.5" color="amber" dense style="display:inline" half-increments readonly
              size="14"></v-rating>

            <span class="grey--text mx-2">
              4.5 of 15 (413 reviews)
            </span>
          </v-card-text>

          <v-card-title class="body-2 mx-6 mt-0 pt-0">This will be listener’s biography. Ex: Lorem ipsum dolor sit amet
            consectetur. Varius malesuada est augue tellus nulla cursus. Lorem ipsum dolor sit amet consectetur. Varius
            malesuada est augue tellus nulla cursus.</v-card-title>
          <p style="color: #220660;font-weight:600" class="mx-6 px-6 text-center">$19 <span class="caption">per
              session</span></p>

          <div class="mx-5">
            <v-btn color="elevation-0" block dark style="background: #220660" class="rounded-lg">
              Make Appoinment
            </v-btn>
            <v-btn elevation="0" dark class="rounded-lg my-3 " block style="background: #F91E5A;">Call Now</v-btn>
          </div>


        </v-card>
      </v-row>


      <v-row class="mt-6 py-6 pb-12 pb-md-6">
        <v-col cols="12">
          <h2 class="text-center" style="color: #F91E5A;">Select Package</h2>
        </v-col>
        <v-col cols="10" sm="10" md="6" lg="6" class="mx-auto">
          <v-row>
            <v-col cols="12" sm="12" md="6" lg="6">
              <v-card elevation="0">
                <v-card-title class="justify-center" style="color: #220660;">For Free</v-card-title>
                <v-card-subtitle class="text-center mx-6">Opportunity to chat for 30 minutes once a week with any
                  listener of your choice.</v-card-subtitle>
                <v-card-text><v-text-field outlined dense placeholder="Enter your e-mail address"></v-text-field>
                  <v-btn class="text-capitalize mt-0 pt-0" elevation="0"
                    style="color: #F91E5A;border :1px solid #F91E5A; background:white"
                    block>Submit</v-btn></v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="12" md="6" lg="6" class="">
              <v-card elevation="0"
                style="border: 1px solid #220660;border-radius: 8px;box-shadow: 0px 0px 24px rgba(34, 6, 96, 0.15);">
                <v-card-title class="justify-center" style="color: #220660;">Paid</v-card-title>
                <v-card-subtitle class="text-center mx-6">Opportunity to chat for 30 minutes once a week with any
                  listener of your choice.</v-card-subtitle>
                <v-card-text class="">
                  <h1 class="text-center my-2 mb-6 pb-3" style="color: #220660;">$19</h1>
                  <v-btn dark elevation="0" class="text-capitalize mt-6" color="#F91E5A" block>Submit</v-btn>
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </v-col>

      </v-row>
    </div>
  </v-container-fluid>
</template>