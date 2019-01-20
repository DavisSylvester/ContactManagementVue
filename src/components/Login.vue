<template>
  <div id="login-container">
    <button v-if="isLoggedIn" class="btn-login">Login</button>

  </div>
</template>

<script>
export default {
  data: function() {
    return {
      isLoggedIn: true
    };
  }
};
</script>


<style lang="less" scoped>
@import "../less/variables.less";

.btn-login {
  justify-self: flex-end;
  align-self: center;
  // height: @headerHeight - 2;
  padding: 3px 30px;
  font-family: "Open Sans";
  font-size: 18px;
  border-bottom-left-radius: 4px;
  border-bottom-right-radius: 4px;
  border-top-left-radius: 2px;
  border-top-right-radius: 2px;
  margin-right: 1%;
  color: #fff;
  background: @darkRedBorderColor;
  border-top-color: @darkRedBorderColor;
  border-right-color: @darkRedBorderColor;
  border-left-color: @darkRedBorderColor;
  border-bottom-color: darken(@darkRedBorderColor, 9%);
  border-bottom-width: 2px;
}
</style>