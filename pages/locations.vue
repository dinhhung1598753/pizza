<template>
  <div class="content">
    <div class="main-img">
      <img src="https://pizza4ps.com/img2017/location/img_main.webp" alt="" />
      <h2 class="title">Location</h2>
      <div class="block_list_locations">
        <span class="item_location">Hai Phong</span
        ><span class="separator">|</span>
        <span class="item_location">Ho Chi Minh</span
        ><span class="separator">|</span>
        <span class="item_location">Ha Noi</span
        ><span class="separator">|</span>
        <span class="item_location">Da Nang</span
        ><span class="separator">|</span>
        <span class="item_location">Nha Trang</span
        ><span class="separator">|</span>
        <span class="item_location">Phnom Penh</span>
      </div>
    </div>
    <section class="content-wrap">
      <div class="header_location">
        <div class="box_title">
          <span class="separator">|</span
          ><span class="location_name">Hai Phong</span>
        </div>
      </div>
      <div class="intro">
        <div class="box_btn_reservation">
          <div class="btn_reservation">
            <img
              src="https://pizza4ps.com/common2017/img/other/ico_reser.png"
              alt=""
            />
            <span class="btn_name">Reservation Online</span>
          </div>
        </div>
        <div class="left">
          <span class="title_page">Location</span><br />
          <!-- <span>Hai Phong</span><span class="separator">|</span>
          <span>Ho Chi Minh</span><span class="separator">|</span>
          <span>Ha Noi</span><span class="separator">|</span>
          <span>Da Nang</span><span class="separator">|</span>
          <span>Nha Trang</span><span class="separator">|</span>
          <span>Phnom Penh</span> -->
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
  name: 'LocationsPage',
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
  & > .block_list_locations {
    position: absolute;
    width: 100%;
    top: 60%;
    text-align: center;
    color: #fff;
    font-size: 20px !important;
    line-height: 60px;
    font-family: 'CenturyStd-LightCondensed-VH', l serif !important;
    > .separator {
      margin-left: 20px;
      margin-right: 20px;
    }
    > .item_location {
      cursor: pointer;
    }
    > .item_location:hover {
      color: #9eaf3b;
    }
  }
}

.content-wrap {
  background: url('https://pizza4ps.com//common2017/img/other/bg_grey2.gif')
    no-repeat 100px -70px;
  > .header_location {
    padding: 4em;
    background: url('https://pizza4ps.com//common2017/img/other/bg_grey1.jpg');
    > .box_title {
      max-width: 1000px;
      margin: 0 auto;
      font-family: CenturyStd-LightCondensed-VH, serif;
      font-size: 30px;
      color: white;
      letter-spacing: 3px;
      > .separator {
        margin-right: 20px;
      }
    }
  }
  > .intro {
    display: flex;
    padding: 90px 0;
    max-width: 60%;
    flex-wrap: wrap;
    margin: 0 auto;
    > .box_btn_reservation {
      width: 100%;
      display: flex;
      justify-content: center;
      margin: 0 auto;
      > .btn_reservation {
        cursor: pointer;
        background: #394f80;
        color: white;
        display: flex;
        justify-content: center;
        width: 450px;
        > img {
          width: 29px;
          height: 29px;
          margin-right: 16px;
          margin-top: 4px;
        }
        > .btn_name {
          font-size: 24px;
        }
      }
      > .btn_reservation:hover {
        opacity: 0.6;
      }
    }
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
