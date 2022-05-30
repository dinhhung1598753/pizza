<template>
  <div class="content">
    <div class="main-img">
      <img src="https://pizza4ps.com/img2017/news/img_main_news.jpg" alt="" />
      <h2 class="title">New & Media</h2>
    </div>
    <section class="content-wrap">
      <div class="intro">
        <div class="catList">
          <span class="btn_category">All</span>
          <span class="separation">|</span>
          <span class="btn_category">Media</span>
          <span class="separation">|</span>
          <span class="btn_category">News</span>
        </div>
        <div class="news_of_block">
          <section class="newsBlock">
            <div class="primary">
              <div class="item_news">
                <div class="top_block">
                  <h3 class="title_new">
                    WE’RE BACK WITH A NEW SEASONAL MENU ✨ 4P’S VERY FIRST
                    LINGUINE DISH
                  </h3>
                  <div class="extra_info">
                    <span>Date : 2022/05/25</span>
                    <span class="separation">|</span>
                    <span>Category : News</span>
                  </div>
                </div>
                <div class="bot_block">
                  <div class="left"></div>
                  <div class="right"></div>
                </div>
              </div>
            </div>
            <div class="secondary">b</div>
          </section>
        </div>
        <!-- <div class="left">
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
        </div> -->
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
  background: url('https://pizza4ps.com/common2017/img/other/bg_body.gif')
    no-repeat 100px -70px;
  > .intro {
    display: flex;
    padding: 90px 0;
    flex-wrap: wrap;
    > .catList {
      width: 100%;
      padding: 4em;
      color: white;
      font-size: 18px;
      font-family: 'CenturyStd-LightCondensed-VH', l serif;
      display: flex;
      justify-content: center;
      > .separation {
        margin-left: 20px;
        margin-right: 20px;
      }
      > .btn_category {
        cursor: pointer;
      }
      > .btn_category:hover {
        color: #9eaf3b;
      }
    }
    > .news_of_block {
      width: 100%;
      > .newsBlock {
        max-width: 1040px;
        padding: 0 20px;
        margin: 0 auto;
        color: white;
        display: flex;
        justify-content: space-between;
        > .primary {
          width: 72%;
        }
        > .secondary {
          width: 15%;
        }
      }
    }
    // > .left {
    //   width: 50%;
    //   text-align: center;
    //   font-size: 40px;
    //   font-family: 'CenturyStd-LightCondensed-VH', l serif;
    // }
    // > .right {
    //   width: 50%;
    //   padding: 0 20px;
    //   line-height: 2.1;
    // }
  }
}
</style>
