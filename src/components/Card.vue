<script>
export default {
    props: {
        img: String,
        series: String
    }
}
</script>

<template lang="">
    <div class="card">
        <img :src="img" >
        <h3>{{ series }}</h3>
    </div>
</template>

<style lang="scss" scoped>
img {
    width: 140px;
    height: 140px;
    margin: 30px 10px 0 0;
}

h3 {
    font-size: 11px;
    margin-top: 8px;
}
</style>