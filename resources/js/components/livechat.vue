<template>
    <div class="row bg-blue margin-row">
        <b-container>
            <b-row class="m-3">
                <div class="col " >
                    <h2 class="text-white ml-3 mt-3">
                        Perlu <b>BANTUAN?</b> Hubungi Kami : <b>0274-5305505</b>
                    </h2>
                </div>
                <div class="col-md-auto"></div>
                <div class="col col-lg-2 col-sm-12 col-md-12 mt-2 text-center">
                    <b-button class="btn-white" pill 
                        ><font-awesome-icon
                            :icon="['fas', 'comments']"
                            class="mr-3"
                    />Live Chat</b-button>
                </div>
            </b-row>
        </b-container>
    </div>
</template>

<script>
export default {
    data() {
        return {
            itemtop: [
                { title: "0274-535055", icon: "phone-alt" },
                { title: "Live Chat", icon: "comment-alt" },
                { title: "Member Area", icon: "user-circle" }
            ],
            right: null
        };
    },
    mounted() {
        console.log("Component mounted.");
    }
};
</script>
<style scoped>
.bg-blue {
    background: #00a2f3;

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
    color: #ffffff;
}
</style>
