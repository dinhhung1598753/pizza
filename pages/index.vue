<template>
  <div class="content">
    <div class="main-img">
      <img src="https://pizza4ps.com/img2017/top/img_main.jpg" alt="" />
      <h2 class="title">Delivering Wow,<br />Sharing Happiness</h2>
    </div>
    <section class="content-wrap">
      <div class="intro">
        <div class="left">
          <span>Welcome to </span>
          <span>Pizza 4P's</span>
        </div>
        <div class="right">
          <p>
            With our mission of "Delivering Wow, Sharing Happiness," we have
            been striving every day to provide the best dining experience to all
            of our dear guests. A restaurant should not be a place to simply
            have a meal. We truly want every guest to leave happy with our food,
            service, and environment that delivers the "Wow" factor. We continue
            to evolve and improve every day so that we can always fulfill our
            mission of "Delivering Wow, Sharing Happiness" to every guest.
          </p>
          <p>About Pizza 4P's</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
<style lang="scss" scoped>
.content {
  color: #fff;
}
.main-img {
  position: relative;
  & > img {
    object-fit: cover;
    width: 100%;
  }
  & > .title {
    position: absolute;
    width: 100%;
    top: 50%;
    text-align: center;
    color: #fff;
    font-size: 50px !important;
    line-height: 60px;
    font-family: 'CenturyStd-LightCondensed-VH', l serif !important;
  }
}

.content-wrap {
  background: url('https://pizza4ps.com//img2017/top/img_01.webp') no-repeat
    100px -70px;
  > .intro {
    display: flex;
    padding: 90px 0;
    > .left {
      width: 50%;
      text-align: center;
      font-size: 40px;
      font-family: 'CenturyStd-LightCondensed-VH', l serif;
    }
    > .right {
      width: 50%;
      padding: 0 20px;
      line-height: 2.1;
    }
  }
}
</style>
