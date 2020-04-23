<template>
<b-container>
  <b-row class="justify-content-center align-items-center">
    <b-col class="justify-content-center align-items-center column-style text-center" v-for="item in fitur" :key="item.key">
        <embed class="fitur-img img-fluid" :src="item.image"/>
        <h5 class="text-center">{{item.title}}</h5>
    </b-col>
  </b-row>
</b-container>
</template>

<script>
export default {
    data(){
        return {
            fitur: [
              { image: 'assets/svg/zendguard.svg',title:'PHP Zend Guard Loader' },
              { image: 'assets/svg/icon PHP Hosting_composer.svg', title:'Composer' },
              { image: 'assets/svg/icon PHP Hosting_ioncube.svg',title:'IonCube' },
            ],
            right: null,
          }    
    }
}
</script>

<style scoped>
.fitur-img{
  width: 150px;
  height: 150px;
}
.img-fluid{
  max-width: 100%;
}
.column-style{
  position: relative;
  width: 100%;
}
</style>