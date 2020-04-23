<template>
    <div class="row bg-footer margin-row">
        <b-container>
            <b-row class="mt-3">
            <b-col class=" col-3">
                
                <ul >
                    <h5><b>Hubungi Kami</b> </h5>
                    <li v-for="item in col1" :key="item.key" v-html="item.text">
                    </li>
                </ul>
            </b-col>
            <b-col class=" col-3">
                <ul>
                    <h5><b>Layanan</b> </h5>
                    <li v-for="item in col2" :key="item.key">
                        {{ item.text }}
                    </li>
                </ul>
            </b-col>
            <b-col class=" col-3">
                <ul>
                    <h5><b>Service Hosting </b></h5>
                    <li v-for="item in col3" :key="item.key">
                        {{ item.text }}
                    </li>
                </ul>
            </b-col>
            <b-col class=" col-3">
                <ul>
                    <h5><b>Tutorial</b></h5>
                    <li v-for="item in col4" :key="item.key">
                        {{ item.text }}
                    </li>
                </ul>
            </b-col>
            <b-col class=" col-3">
                <ul>
                    <h5><b>Tentang Kami</b></h5>
                    <li v-for="item in col5" :key="item.key">
                        {{ item.text }}
                    </li>
                </ul>
            </b-col>
            <b-col class=" col-3">
                <ul>
                    <h5><b>Kenapa Pilih Niagahoster?</b></h5>
                    <li v-for="item in col6" :key="item.key">
                        {{ item.text }}
                    </li>
                </ul>
            </b-col>
        </b-row>
        </b-container>
    </div>
</template>

<script>
export default {
    data(){
        return {
            col1: [
              { text: 'Telp: 0274-2885822' },
              { text: 'WA: 0895422447394'},
              { text: 'Senin - Minggu' },
              { text: '24 Jam Non Stop' },
              { text: '\n \n \n '},
              { text: 'Jl. Palagan Tentara Pelajar' },
              { text: 'No 81 Jongkang, Sariharjo,' },
              { text: 'Ngaglik, Sleman' },
              { text: 'Daerah Istimewa Yogyakarta' },
              { text: '55581' },
            ],
            col2: [
              { text: 'Domain' },
              { text: 'Shared Hosting'},
              { text: 'Cloud Hosting' },
              { text: 'Cloud VPS Hosting' },
              { text: 'Transfer Hosting' },
              { text: 'Web Builder' },
              { text: 'Keamanan SSL/HTTPS' },
              { text: 'Jasa Pembuatan Website' },
              { text: 'Program Afiliasi' },
              { text: 'Whois' }
            ],
            col3:[
                {text: 'Hosting Murah'},
                {text: 'Hosting Indonesia'},
                {text: 'Hosting Singapore SG'},
                {text: 'Hosting Wordpress'},
                {text: 'Email Hosting'},
                {text: 'Reseller Hosting'},
                {text: 'Web Hosting Unlimited'}
            ],
            col4:[
                {text:'Knowledge Base'},
                {text:'Blog'},
                {text:'Cara Pembayaran'},
            ],
            col5:[
                {text:'Tentang'},
                {text:'Penawaran & Promo Spesial'},
                {text:'Niaga Poin'},
                {text:'Karir'},
                {text:'Kontak Kami'}
            ],
            col6:[
                {text:'Hosting Terbaik'},
                {text:'Datacenter Hosting Terbaik'},
                {text:'Domain Gratis'},
                {text:'Bagi-bagi Domain Gratis'},
                {text:'Bagi-bagi Hosting Gratis'},
                {text:'Review Pelanggan'},
            ],
            right: null,
          }    
    }
};
</script>
<style scoped>
.bg-footer {
    background: #303030;
}
.margin-row{
  padding-top: 50px;
  padding-bottom: 50px;
}
.btn-white{
  background-color: #00a2f3;
  width: 200px;
  border-color: #ffffff;
  border: 2px solid;
}
.text-white {
  
}
ul {
  list-style-type: none;
    color: #8C8C8C;
 }
</style>
