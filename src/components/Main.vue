<script>
export default {

}
</script>

<template lang="">
    <div>
        <div class="background">
            <div class="sub-container">
                <div class="content">
                    --&lt Content goes here &lt--
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.background {
    background-color: black;

    .sub-container {
        width: 60%;
        margin: 0 auto;

        .content {
            color: white;
            font-size: 18px;
            padding: 40px 0;
        }
    }
}
</style>