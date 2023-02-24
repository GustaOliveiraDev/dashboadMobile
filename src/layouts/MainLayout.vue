<template>
  <q-layout class="bg-teal-14 col-12 q-gutter-y-md ">
    <div class=" bg-teal col-12 flex flex-center  text-h5">
     <div class="q-pa-md">
      Saúde CGE
     </div>
    </div>
    <div class="col-12 flex flex-center q-gutter-x-md">

      <q-btn class="bg-white text-teal-14" push rounded label="Radar" />
      <q-btn class="bg-white text-teal-14" push rounded label="Radar" />
      <q-btn class="bg-white text-teal-14" push rounded label="Radar" />

    </div>

     <div class="flex flex-center">
      <Card />
     </div>
    
  </q-layout>
</template>

<script>
import Card from 'src/components/mainCard.vue'

export default{
  components: {
    Card,
  }
 
}


</script>



<style>
.text-green2 {
  background: #00796b;
}

.bg-green2 {
  background: #00796b;
}

.bg-white {
  background: #FFFFFF;
}
</style>