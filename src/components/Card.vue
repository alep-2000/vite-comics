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

<style lang="scss"></style>