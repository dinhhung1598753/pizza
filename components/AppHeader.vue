<template>
  <div class="header">
    <div class="app-logo">
      <a href="/">
        <img
          src="https://pizza4ps.com/common2017/img/header/logo_white.svg"
          alt="Pizza4P's"
        />
      </a>
    </div>
  </div>
</template>
<script>
export default {
  name: 'AppHeader',
}
</script>
<style scoped>
.app-logo {
  float: left;
  padding: 19px 0 0 28px;
}

.header {
  position: fixed;
  height: 100px;
  background-color: rgb(0 0 0 / 80%);
  width: 100%;
}

.header img {
  display: inline-block;
  vertical-align: text-bottom;
  width: 130px;
}
</style>
>
