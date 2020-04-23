<template>
<b-container class="mt-5">
        
  <b-row class="mt-4">
    
    <b-col sm="12" xs="12" md="6">
        
        <h2 class="line-height">
            Linux Hosting yang Stabil dengan Teknologi LVE 
        </h2>

        <span>
            SuperMicro <b>Intel Xeon 24-Cores</b> server dengan RAM 128GB dan teknologi <b>LVE CloudLinux</b> untuk 
            stabilitas server anda. Dilengkapi dengan <b>SSD</b> untuk kecepatan <b>MySQL</b> dan caching. Apache load balancer
            dan auto backup untuk keamanan website PHP anda. 
        </span>

        <b-button class="btn-style text-bold" pill variant="primary">Pilih Hosting Anda</b-button>
    </b-col>
    <b-col>
        <img class="image-linux" src="assets/images/Image support.png">    
    </b-col>
  </b-row>
</b-container>
</template>

<script>
export default {
    data(){
        return {
            benefit: [
              { text: 'Install Laravel <b>1 Klik</b> dengan Softaculous Installer.' },
            ],
            right: null,
          }    
    }
}
</script>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');

    .text-bold{
         font-family:'Montserrat', sans-serif;
        font-weight: 700;
    }
    .btn-style{
      padding: 10px 20px 10px 20px; 
      margin-top: 20px;
      font-size: 18px;
    }
    .image-linux{
      max-width: 500px;
    }
</style>