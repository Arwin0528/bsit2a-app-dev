<template>
  <div>
    
    <v-row>
   <v-col cols="12" md="3">
    <v-card height="120" color="red">
      <v-card-text>
        <v-row>
          <v-col cols="6">
            <v-icon size="80">mdi-account circle</v-icon>
          </v-col>
          <v-col cols="50">
            
           <v-row no-gutters>
            <v-col  cols="12" class="text-h6 text-right text-uppercase ">Student</v-col>
            <v-col  cols="12" class="text-h4 text-right font-weight-bold">120</v-col>

            </v-row>
          </v-col>
        </v-row>
      </v-card-text>
    </v-card>

    </v-col>
 
     
  
   <v-col cols="12" md="3">
    <v-card height="120" color="blue">
      <v-card-text>
        <v-row>
          <v-col cols="6">
            <v-icon size="80">mdi-account circle</v-icon>
             </v-col>
            <v-col cols="50">
           
              <v-row no no-gutters>
              <v-col cols="12" class="text-h6 text-right text-uppercase ">Account</v-col>
               <v-col cols="12" class="text-h4 text-right font-weigth-bold">123</v-col>
            </v-row>
            </v-col>
         
        </v-row>
      </v-card-text>
    </v-card>
   </v-col>

   
   <v-col cols="12" md="3">
    <v-card height="120" color="yellow">
      <v-card-text>
        <v-row>
          <v-col cols="6">
            <v-icon size="80">mdi-account circle</v-icon>
             </v-col>
            <v-col cols="50">
           
              <v-row no no-gutters>
              <v-col cols="12" class="text-h6  text-right text-uppercase">Account</v-col>
               <v-col cols="12" class="text-h4 text-right font-weigth-bold">150</v-col>
            </v-row>
            </v-col>
         
        </v-row>
      </v-card-text>
    </v-card>
   </v-col>


   <v-col cols="12" md="3">
    <v-card height="120" color="gray">
      <v-card-text>
        <v-row>
          <v-col cols="6">
            <v-icon size="80">mdi-account circle</v-icon>
             </v-col>
            <v-col cols="50">
           
              <v-row no no-gutters>
              <v-col cols="12" class="text-h6 text-right text-uppercase">Account</v-col>
               <v-col cols="12" class="text-h4 text-right font-weigth-bold">228</v-col>
            </v-row>
            </v-col>
          
         
        </v-row>
      </v-card-text>
    </v-card>
   </v-col>
    </v-row>    
      

       <v-row>
      <v-col cols="12" md="8">
      <v-card height="500" color="#EEEEEE" elevation="0">
        <v-card-text>
          <v-data-table 
          density="compact"
          item-key="name"> 
          </v-data-table>
        </v-card-text>
      </v-card>
       </v-col>
      
       
       <v-col>
        <v-row>
          <v-col cols="12">
          <v-card height="150" color="#EEEEEE" elevation="0"></v-card>
          </v-col>
        </v-row>
       </v-col>         

       <v-col>
        <v-row>
          <v-col cols="12">
          <v-card height="150" color="#EEEEEE"></v-card>
          </v-col>
        </v-row>
       </v-col>


       <v-col>
        <v-row>
          <v-col cols="12">
          <v-card height="150" color="#EEEEEE"></v-card>
          </v-col>
        </v-row>
       </v-col>
        </v-row>
       
    
   

  </div>
</template>

<script lang="ts" setup>

</script>

<style> 

</style>

    

