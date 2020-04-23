<template>
    <b-container class="mt-5">
        <b-row>
            <b-col class="text-center">
                <h2>Modul Lengkap untuk Menalankan Aplikasi PHP Anda</h2>
            </b-col>
        </b-row>
        <b-row class="mt-3">
            <b-col class="ml-5 mt-4">
                <ul >
                    <li v-for="item in col1" :key="item.key">
                        {{ item.text }}
                    </li>
                </ul>
            </b-col>
            <b-col class="ml-5 mt-4">
                <ul>
                    <li v-for="item in col2" :key="item.key">
                        {{ item.text }}
                    </li>
                </ul>
            </b-col>
            <b-col class="ml-5 mt-4">
                <ul>
                    <li v-for="item in col3" :key="item.key">
                        {{ item.text }}
                    </li>
                </ul>
            </b-col>
            <b-col class="ml-5 mt-4">
                <ul>
                    <li v-for="item in col4" :key="item.key">
                        {{ item.text }}
                    </li>
                </ul>
            </b-col>
        </b-row>
        <b-row>
            <b-col class="text-center">
                <b-button class="btn-style" pill variant="outline-secondary">Selengkapnya</b-button>
            </b-col>
        </b-row>
        
    </b-container>
</template>

<script>
export default {
    data(){
        return {
            col1: [
              { text: 'IcePHP' },
              { text: 'apc'},
              { text: 'apcu' },
              { text: 'apm' },
              { text: 'ares' },
              { text: 'bcmath' },
              { text: 'bcompiler' },
              { text: 'big_init' },
              { text: 'bitset' },
              { text: 'bloomy' },
              { text: 'bz2_filter' },
              { text: 'clamav' },
              { text: 'coin_acceptor' },
              { text: 'crack' },
              { text: 'dba' }
            ],
            col2: [
              { text: 'http' },
              { text: 'huffman'},
              { text: 'idn' },
              { text: 'igbinary' },
              { text: 'imagick' },
              { text: 'imap' },
              { text: 'include' },
              { text: 'inotify' },
              { text: 'interbase' },
              { text: 'intl' },
              { text: 'ioncube_loader' },
              { text: 'ioncube_loader_4' },
              { text: 'jsmin' },
              { text: 'json' },
              { text: 'ldap' }
            ],
            col3:[
                {text: 'nd_pdo_mysql'},
                {text: 'oauth'},
                {text: 'oci8'},
                {text: 'odbc'},
                {text: 'opcache'},
                {text: 'pdf'},
                {text: 'pdo'},
                {text: 'pdo_dblib'},
                {text: 'pdo_firebird'},
                {text: 'pdo_mysql'},
                {text: 'pdo_odbc'},
                {text: 'pdo_pgsql'},
                {text: 'pdo_sqlite'},
                {text: 'pgsql'},
                {text: 'phalcon'},
            ],
            col4:[
                {text:'stats'},
                {text:'stem'},
                {text:'stomp'},
                {text:'suhosin'},
                {text:'sybase_ct'},
                {text:'sysvmsg'},
                {text:'sysvsem'},
                {text:'sysvshm'},
                {text:'tidy'},
                {text:'timezonedb'},
                {text:'trader'},
                {text:'translit'},
                {text:'uploadprogress'},
                {text:'uri_template'},
                {text:'uuid'},
            ],
            right: null,
          }    
    }
}
</script>

<style scoped>
ul {
  list-style-type: none;
 }
 .btn-style{
      padding: 10px 20px 10px 20px; 
      margin-top: 20px;
      font-size: 18px;
    }
</style>