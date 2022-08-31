<template>
  <div>
  <v-card 
  color="black"
  height="4"
    width="596"
      shaped
    tile
  >
  </v-card>
  
  <v-card
  color="black"
  height="588"
    width="596"
      shaped
    tile
  >
  <div id="board_1">
  <v-flex 
  class="d-flex justify-space-between mx-1">
  <v-sheet 
  v-for="board_a in 8" 
  :key="board_a" class="list" :id="'board_a' + board_a"
    color="green lighten-1"
    height="70"
    width="70"
    fab
    tile
  > 
  </v-sheet>
  </v-flex>
  </div>
  
  <div id="board_2">
  <v-flex my-1
  class="d-flex justify-space-between mx-1">
  <v-sheet 
  v-for="board_b in 8"
  :key="board_b" class="list_b" :id="'board_b' + board_b"
    color="green darken-1"
    height="70"
    width="70"
    fab
    tile
  > 
  </v-sheet>
  </v-flex>
  </div>
  
  <div id="board_3">
  <v-flex my-1
  class="d-flex justify-space-between mx-1">
  <v-sheet 
  v-for="board_c in 8"
  :key="board_c" class="list_c" :id="'board_c' + board_c"
    color="green lighten-1"
    height="70"
    width="70"
    fab
    tile
  > 
  </v-sheet>
  </v-flex>
  </div>
  
  <div id="board_4">
  <v-flex my-1
  class="d-flex justify-space-between mx-1">
  <v-sheet 
  v-for="board_d in 8"
  :key="board_d" class="list_d" :id="'board_d' + board_d"
    color="green darken-1"
    height="70"
    width="70"
    fab
    tile
  > 
  <div class="stone">
</div>
  </v-sheet>
  </v-flex>
  </div>
  
  <div id="board_5">
  <v-flex my-1
  class="d-flex justify-space-between mx-1">
  <v-sheet 
  v-for="board_e in 8"
  :key="board_e" class="list_e" :id="'board_e' + board_e"
    color="green lighten-1"
    height="70"
    width="70"
    fab
    tile
  > 
  </v-sheet>
  </v-flex>
  </div>
  
  <div id="board_6">
  <v-flex my-1
  class="d-flex justify-space-between mx-1">
  <v-sheet 
  v-for="board_f in 8"
  :key="board_f" class="list_f" :id="'board_f' + board_f"
    color="green darken-1"
    height="70"
    width="70"
    fab
    tile
  > 

  </v-sheet>
  </v-flex>
  </div>
  
  <div id="board_7">
  <v-flex my-1
  class="d-flex justify-space-between mx-1">
  <v-sheet 
  v-for="board_g in 8"
  :key="board_g" class="list_g" :id="'board_g' + board_g"
    color="green lighten-1"
    height="70"
    width="70"
    fab
    tile
  > 

  </v-sheet>
  </v-flex>
  </div>


  <div id="board_8">
  <v-flex my-1
  class="d-flex justify-space-between mx-1">
  <v-sheet 
  v-for="board_h in 8"
  :key="board_h" class="list" :id="'board_h' + board_h"
    color="green darken-1"
    height="70"
    width="70"
    fab
    tile
  > 
  </v-sheet>
  </v-flex>
  </div>
  
  </v-card>
  
    <v-card
  color="black"
  height="4"
  width="596"
      shaped
      tile
  >
  </v-card>
  
  
  
  </div>
  </template>


<style>

.stone {
  position: absolute;
  top: 2px;
  bottom: 0;
  left: 2px;
  width: 42px;
  height: 42px;
  border-radius: 21px;
}

.stone[data-state="0"] {
  display: none;
}

.stone[data-state="1"] {
color: black;
}

.stone[data-state="2"] {
color: white;
}
</style>

<script>

(( )=>{

const $doc = document;

var stage_1 = [];

for (var i = 0; i < 8; ++i) {
  stage_1.push(document.getElementById("board_a" + i));
}

var stage_2 = [];

for (var i = 0; i < 8; ++i) {
  stage_2.push(document.getElementById("board_b" + i));
}

var stage_3 = [];

for (var i = 0; i < 8; ++i) {
  stage_3.push(document.getElementById("board_c" + i));
}

var stage_4 = [];

for (var i = 0; i < 8; ++i) {
  stage_4.push(document.getElementById("board_d" + i));
}

var stage_5 = [];

for (var i = 0; i < 8; ++i) {
  stage_5.push(document.getElementById("board_e" + i));
}

var stage_6 = [];

for (var i = 0; i < 8; ++i) {
  stage_6.push(document.getElementById("board_f" + i));
}

var stage_7 = [];

for (var i = 0; i < 8; ++i) {
  stage_7.push(document.getElementById("board_g" + i));
}

var stage_8 = [];

for (var i = 0; i < 8; ++i) {
  stage_8.push(document.getElementById("board_h" + i));
}






  }


)();

</script>
