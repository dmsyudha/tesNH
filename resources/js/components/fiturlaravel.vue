<template>
    <b-container class="mt-5">
        <b-row>
            <b-col class="text-center">
                <h2>Mendukung Penuh Framework Laravel</h2>
            </b-col>
        </b-row>
        <b-row class="mt-4">
            <b-col sm="12" xs="12" md="6">
                <h5 class="line-height">
                    Tak perlu menggunakan dedicated server ataupun VPS yang
                    mahal. Layanan PHP hosting murah kami mendukung penuh
                    framework favorit Anda
                </h5>
                <div class="pt-2" v-for="item in benefit" :key="item.key">
                    <font-awesome-icon
                        icon="check-circle"
                        class="mr-2"
                        :style="{ color: '#00B348' }"
                    />
                    <span v-html="item.text"></span>
                </div>
                <p class="small-text">
                    Nb. Composer dan SSH hanya tersedia pada paket Personal
                    Bisnis
                </p>
                <b-button class="btn-style text-bold" pill variant="primary"
                    >Pilih Hosting Anda</b-button
                >
            </b-col>
            <b-col sm="12" xs="12" md="6">
                <img src="assets/svg/illustration banner PHP hosting-01.svg" />
            </b-col>
        </b-row>
    </b-container>
</template>

<script>
export default {
    data() {
        return {
            benefit: [
                {
                    text:
                        "Install Laravel <b>1 Klik</b> dengan Softaculous Installer."
                },
                {
                    text:
                        "Mendukung ekstensi <b>PHP MCrypt, phar, mbstring, json,</b> dan <b>fileinfo.</b>"
                },
                {
                    text:
                        "Tersedia Composer dan SSH untuk menginstal packages pilihan Anda."
                }
            ],
            right: null
        };
    }
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap");

.text-bold {
    font-family: "Montserrat", sans-serif;
    font-weight: 700;
}
.btn-style {
    padding: 10px 20px 10px 20px;
    margin-top: 20px;
    font-size: 18px;
}
.line-height {
    letter-spacing: 1px;
    line-height: 1.5;
}
.small-text {
    margin-top: 20px;
    font-size: 12px;
}
</style>
