<template>
    <b-container class="mt-4">
        <b-row>
            <b-col class="text-center">
                <h2>Semua Paket Sudah Termasuk Hosting</h2>
            </b-col>
        </b-row>
        <b-row>
            <b-col class="column-style text-center" v-for="item in fitur1" :key="item.key">
                <img class="fitur-img img-fluid" :src="item.image"/>
                <h5 class="text-center text-bold">{{item.title}}</h5>
                <p class="text-center">{{item.caption}}</p>
            </b-col>
        </b-row>
        <b-row>
            <b-col class="column-style text-center" v-for="item in fitur2" :key="item.key">
                <img class="fitur-img img-fluid" :src="item.image"/>
                <h5 class="text-center text-bold">{{item.title}}</h5>
                <p class="text-center">{{item.caption}}</p>
            </b-col>
        </b-row>
        
    </b-container>
</template>

<script>
export default {
data(){
        return {
            fitur1: [
              { image: 'assets/svg/icon PHP Hosting_PHP Semua Versi.svg',title:'PHP Semua Versi',caption:'Pilih mulai dari Versi PHP 5.3 s/d PHP 7. Ubah sesuka Anda!' },
              { image: 'assets/svg/icon PHP Hosting_My SQL.svg', title:'MySQL Versi 5.6', caption:'Nikmati MySQL versi terbaru, tercepat dan kaya akan fitur.' },
              { image: 'assets/svg/icon PHP Hosting_CPanel.svg',title:'Panel Hosting cPanel', caption:'Kelola website dengan panel canggih yang familiar di hati Anda.' },
            ],
            fitur2: [
              { image: 'assets/svg/icon PHP Hosting_garansi uptime.svg',title:'Garansi Uptime 99.9%',caption:'Data center yang mendukung kelangsungan website Anda 24/7.' },
              { image: 'assets/svg/icon PHP Hosting_InnoDB.svg', title:'Database InnoDB Unlimited', caption:'Jumlah dan ukuran databsae yang tumbuh sesuai kebutuhan anda' },
              { image: 'assets/svg/icon PHP Hosting_My SQL remote.svg',title:'Wildcard Remote MySQL', caption:'Mendukung s/d 25 max_user_connectios dan 100 max_connection' },
            ],
            right: null,
          }    
    }
}
</script>

<style scoped>
.fitur-img{
  width: 80px;
  height: 80px;
}
.img-fluid{
  max-width: 100%;
}
.column-style{
  position: relative;
  width: 100%;
  margin-top: 40px;
}
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@800&display=swap');
.text-bold{
    font-family:'Montserrat', sans-serif;
    font-weight: 800;
}
</style>