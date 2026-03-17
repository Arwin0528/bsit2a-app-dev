<template>
  <div class="d-flex justify-center align-center" style="height: 100vh;">
  <v-card width="350" class="text-center" elevation="12" >
   
    <!--logo-->
      <v-icon style="font-size: 50px;" color="blue"  class="pt-10">mdi-apple</v-icon>
   <v-card-text class="py-10">
     
    <!--Username TextField-->
     <v-text-field variant="outlined" v-model="username" label="Username" prepend-inner-icon="mdi-account" clearable color="blue">
     </v-text-field>
       
     <!--Password TextField-->
      <v-text-field variant="outlined"  v-model="password"  label="Password" prepend-inner-icon="mdi-lock" type="password" clearable color="blue">
     </v-text-field>

       <!--Signin = Button-->

       <v-btn color="blue" @click="login" block>SIGN IN</v-btn>
  

   </v-card-text>
    
  </v-card>


  </div>
</template>

<script setup>
definePageMeta({
    layout: 'auth',
});
const defaultUsername = ref("admin");
const defaultPassword = ref("admin123")
const username = ref("hello");
const password = ref("sirit");


// Regular function
function login() {
  alert("login succesfull ");
}


// arrow function
const login = () =>{

}
</script>

