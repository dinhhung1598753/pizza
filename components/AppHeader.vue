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
    <div class="app-menu">
      <ul>
        <li class="app-navigation">About</li>
        <li class="app-navigation">Location</li>
        <li class="app-navigation">Menu</li>
        <li class="app-navigation">E-invoice</li>
        <li class="app-navigation">News</li>
        <li class="app-navigation">Activities</li>
        <li class="app-navigation">Career</li>
        <li class="app-navigation">Online store</li>
      </ul>
      <div class="btn reservations"><span>Reservations</span></div>
      <div class="btn delivery">Delivery</div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'AppHeader',
}
</script>
<style lang="scss" scoped>
.header {
  position: fixed;
  height: 100px;
  background-color: rgb(0 0 0 / 80%);
  width: 100%;
  display: flex;
  align-items: center;
  z-index: 1000;
}

.app-logo {
  float: left;
  padding-left: 28px;
}

.app-menu {
  margin-left: auto;
  color: #fff;
  display: flex;
  height: 100%;
  align-items: center;
  > ul {
    display: flex;
    > li {
      margin: 0 10px;
      list-style-type: none;
      &:hover {
        color: #587534;
        cursor: pointer;
      }
    }
  }
  > .btn {
    padding: 5px 10px;
    line-height: 90px;
    &:hover {
      cursor: pointer;
      opacity: 0.5;
      transition: 0.2s;
    }
    &.reservations {
      background-color: #394f80;
    }
    &.delivery {
      background-color: #9eaf3b;
    }
  }
}

.header img {
  display: inline-block;
  vertical-align: text-bottom;
  width: 130px;
}
</style>
>
