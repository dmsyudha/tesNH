<template>
  <b-container>
    <div class="row">
    <div class="col col-xs-12">
      <b-iconstack font-scale="1">
            <b-icon stacked icon="bookmark-fill" variant="primary" scale="4"></b-icon>
            <b-icon stacked icon="tag-fill" variant="light" scale="1.5"></b-icon>
        </b-iconstack>
        <span class="ml-3 mt-2"><small>Gratis Ebook 9 Cara Cerdas Menggunakan Domain [x]</small> </span>
    </div>
    <div class="col-md-auto">
    </div>
    <div class="col col-lg-5 col-xs-6 mt-2">
      <span class="mr-3" v-for="item in itemtop" :key="item.title"><font-awesome-icon :icon="item.icon" class="mr-3" size="2"/>{{item.title}}</span>
    </div>
  </div>
  </b-container>
</template>

<script>
    export default {
        data () {
          return {
            itemtop: [
              { title: '0274-5305505', icon: 'phone-alt' },
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

</style>