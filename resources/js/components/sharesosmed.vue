<template>
    <div class="row bg-grey">
      <b-container>
        <b-row class="m-3">
    <div class="col">
        <p class=" ml-3 mt-3"><b>Bagikan jika anda menyukai halaman ini</b>  </p>
    </div>
    <div class="col-md-auto">
    </div>
    <div class="col col-lg-5 mt-2">
        
      <b-button class="btn-style-fb"><font-awesome-icon :icon="['fab', 'facebook-f']" size="2"/></b-button>
      <b-button class="btn-style">80k</b-button>
      <b-button class="btn-style-twitter"><font-awesome-icon :icon="['fab', 'twitter']" size="2"/></b-button>
      <b-button class="btn-style">450</b-button>
      <b-button class="btn-style-google"><font-awesome-icon :icon="['fab', 'google-plus-g']" size="2"/></b-button>
      <b-button class="btn-style">1900</b-button>
    </div>
    </b-row>
    </b-container>
  </div>
</template>

<script>
    export default {
        data () {
          return {
            itemtop: [
              { title: '0274-535055', icon: 'phone-alt' },
              { title: 'Live Chat', icon: 'comment-alt' },
              { title: 'Member Area', icon: 'user-circle' },
            ],
            right: null,
          }
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
<style scoped>
.bg-grey{
  background: #F7F7F7;
}
.btn-style{
  background-color: #F7F7F7;
  border-color: grey ;
  color: grey;
  width: 80px;
}
.btn-style-fb{
  background-color: #23599B;
  width: 40px;
	border-color: #23599B;
}
.btn-style-twitter{
  width: 40px;
  background-color: #00AEF1;
	border-color: #00AEF1;
}
.btn-style-google{
  width: 40px;
  background-color: #FC4A35;
	border-color: #FC4A35;
}
</style>