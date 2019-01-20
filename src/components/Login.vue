


<template>
<div id="login-container">
    <button class="btn-login">Login</button>
</div>    
</template>

<script>
import '../less/variables.less';

export default {
    
}
</script>


<style lang="less" scoped>

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