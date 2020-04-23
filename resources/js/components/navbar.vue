<template>
<b-container>
  <b-navbar toggleable="lg" type="light">
    <b-navbar-brand href="#">
          <img class="navbrand" src="assets/images/logo.png" alt="Kitten">
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto mt-2" v-for="item in items" :key="item.title"> 
        <span>{{item.title}}</span> 
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</b-container>
</template>

<script>
    export default {
        data () {
          return {
            items: [
              { title: 'Hosting' },
              { title: 'Domain' },
              { title: 'Server' },
              { title: 'Website' },
              { title: 'Afiliasi' },
              { title: 'Promo' },
              { title: 'Pembayaran' },
              { title: 'Review' },
              { title: 'Kontak' },
              { title: 'Blog' },
            ]
          }
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
<style scoped>
.navbrand{
  max-width: 100px;
}

</style>