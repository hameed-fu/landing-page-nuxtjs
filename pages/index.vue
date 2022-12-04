<template>
  <!-- top -->
  <v-container-fluid>
    <v-row>
      <v-col   sm="6" md="6" lg="6" class="d-flex">
          
      </v-col>
      
      <v-col   sm="6" md="6" lg="6">
        <img class="img1" src="../assets/img/img1.png" alt="" width="100%">
        <img class="img2" src="../assets/img/img2.png" alt="" width="100%">
      </v-col>
    </v-row>
    
  </v-container-fluid>
  <!-- end top -->
</template>

<style>
.img1 {
  position: absolute;
  width: 225px;
  height: 336px;
  left: 728px;
  top: 248px;
  padding: 15px;
  background: url('../assets/img/card1.png');
  border-radius: 8px;
  z-index: 1;
}

.img2 {
  position: absolute;
  width: 396px;
  height: 200px;
  left: 792px;
  top: 172px;
  padding: 15px;
  background: url('../assets/img/card2.png');
  border-radius: 8px;
}
 
</style>