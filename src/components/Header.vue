<template>
    <header>
        <div class="logo">Contact Management</div>
    </header>
</template>

<script>
export default {
    
}
</script>


<style lang="less" scoped>


@darkRed: #e0182d;
@darkRedBorderColor: darken(@darkRed, 25%);


header {
    box-sizing: border-box;
    width: 100vw;
    max-width: 100%;
    background:	@darkRed;
    border-bottom: 2px solid @darkRedBorderColor;
    height: 5vh;
    line-height: 5vh;
    color: #fff;
    display: flex;
    padding-left: 0px 10px;
    font-family: "Open Sans";

}

.logo {
    font-size: 2vh;
    margin: 0px 10px;
    font-weight: 600;
}
</style>
