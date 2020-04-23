<template>
<b-container>
  <b-row class="mt-4">
    <b-col >
        <h1 class= "text-slider">PHP Hosting</h1>
        <h2 style="">
            Cepat, handal, penuh dengan modul PHP yang Anda butuhkan
        </h2>
        <div class="p-2" v-for="item in benefit" :key="item.key">
        <span ><font-awesome-icon icon="check-circle" class="mr-2" :style="{ color: '#00B348' }"/>{{item.text}}</span>
        </div>
    </b-col>
    <b-col sm="8" xs="12">
        <img src="assets/svg/illustration banner PHP hosting-01.svg">    
    </b-col>
  </b-row>
</b-container>
</template>

<script>
export default {
    data(){
        return {
            benefit: [
              { text: 'Solusi PHP untu performa query lebih cepat' },
              { text: 'Konsumsi memori yang lebih rendah' },
              { text: 'Support PHP 5.3, PHP 5.4, PHP 5.5, PHP 5.6, PHP 7' },
              { text: 'Fitur enkripsi IonCube dan Zend Guard Loaders' },
            ],
            right: null,
          }    
    }
}
</script>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@800&display=swap');
     .text-slider{
         font-family:'Montserrat', sans-serif;
        font-weight: 800;
    }
</style>