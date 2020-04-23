<template>
    <b-container>
        <b-row>
            <b-col class="text-center mt-5">
                <h2>Powerful dengan Limit PHP yang Lebih Besar</h2>
            </b-col>
        </b-row>
        <b-row>
            <b-col class="ml-lg-5 mt-4">
                <ul class="list-group">
                    <li class="list-group-item"><span ><font-awesome-icon icon="check-circle" class="mr-5 icon-left" :style="{ color: '#00B348' }"/>max execution time 300ms</span></li>
                    <li class="list-group-item"><span ><font-awesome-icon icon="check-circle" class="mr-5 icon-left" :style="{ color: '#00B348' }"/>max execution time 300ms</span></li>
                    <li class="list-group-item"><span ><font-awesome-icon icon="check-circle" class="mr-5 icon-left" :style="{ color: '#00B348' }"/>php memory limit 1024mb</span></li>
                </ul>
            </b-col>
            <b-col class="ml-lg-5 mt-4">
                <ul class="list-group">
                    <li class="list-group-item"><span ><font-awesome-icon icon="check-circle" class="mr-5 icon-left" :style="{ color: '#00B348' }"/>post max size 128 MB</span></li>
                    <li class="list-group-item"><span ><font-awesome-icon icon="check-circle" class="mr-5 icon-left" :style="{ color: '#00B348' }"/>upload max filesize 128 MB</span></li>
                    <li class="list-group-item"><span ><font-awesome-icon icon="check-circle" class="mr-5 icon-left" :style="{ color: '#00B348' }"/>max input vars 2500</span></li>
                </ul>

            </b-col>
        </b-row>
        
    </b-container>
</template>

<script>
export default {

}
</script>

<style scoped>
.list-group-item{
    padding: 5px 5px;
}
.list-group{
    width: 400px;
}
.icon-left{
    margin-left: 10px;
}
</style>