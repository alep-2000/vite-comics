<script>
export default {

}
</script>

<template lang="">
    <div class="jumbotron">
        <div>
            CURRENT SERIES
        </div>
    </div>
</template>

<style lang="scss">
@use '../styles/partials/variables' as *;

.jumbotron {
    width: 100%;
    height: 300px;
    background-image: url('../assets/img/jumbotron.jpg');
    position: relative;

    div {
        color: white;
        width: 160px;
        background-color: $blue;
        text-align: center;
        padding: 6px 0;
        position: absolute;
        bottom: -7%;
        left: 20%;
        transform: translate(-5%, -20%);
    }
}
</style>