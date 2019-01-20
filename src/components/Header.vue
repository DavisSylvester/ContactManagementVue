<template>
    <header>
        <div class="logo">Contact Management</div>
        <div class="spacer"></div>
        <Login></Login>
    </header>
</template>

<script>
import Login from "./Login.vue";

export default {
    
    components: {
    Login
  }
}
</script>


<style lang="less" scoped>
@darkRed: #e0182d;
@darkRedBorderColor: darken(@darkRed, 25%);

@headerHeight: 5vh;

header {
    box-sizing: border-box;
    width: 100vw;
    max-width: 100%;
    background:	@darkRed;
    border-bottom: 2px solid @darkRedBorderColor;
    height: @headerHeight;
    line-height: @headerHeight;
    color: #fff;
    display: flex;
    padding-left: 0px 10px;
    font-family: "Open Sans";
    padding: 0px 10px;
}

.logo {
    font-size: @headerHeight - 3;
    margin: 0px 10px;
    font-weight: 600;
}
header > .spacer {
    flex-grow: 1;
}
.btn-login {
    justify-self: flex-end;
    align-self: center;
    height: @headerHeight - 2;
    padding: 0px 30px;
    font-family: 'Open Sans';
    font-size: 18px;
    border-bottom-left-radius: 4px;
    border-bottom-right-radius: 4px;
    border-top-left-radius: 2px;
    border-top-right-radius: 2px;
    margin-right: 1%;
    background: @darkRedBorderColor;
    color: #fff;
    border-top-color: @darkRedBorderColor;
    border-right-color: @darkRedBorderColor;
    border-left-color: @darkRedBorderColor;
    border-bottom-color:darken(@darkRedBorderColor, 9%);
    border-bottom-width: 2px;
}
</style>
