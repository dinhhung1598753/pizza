<template>
  <div>
    <div class="career-header">
      <div class="logo">
        <img
          src="https://datax-talent.basecdn.net/pizza4p/logo-footer.png"
          alt=""
        />
      </div>
      <div class="menu">
        <ul class="list">
          <li class="item">
            <a href="https://pizza4ps.com/" target="_blank">Who Are We</a>
          </li>
          <li class="item"><a href="#alljobs">HOT Jobs</a></li>
          <li class="item"><a href="#benefits">What We Offer</a></li>
        </ul>
      </div>
    </div>

    <div class="career-slider">
      <div class="slider">
        <carousel-parent :slides="slides" />
      </div>
      <div class="search">
        <input
          class="text"
          type="text"
          placeholder="Vị trí, chức danh, kỹ năng..."
        />
        <div class="service">
          <select>
            <option>Ngành nghề</option>
            <option>Service(Phục vụ)</option>
            <option>Ngành nghề</option>
            <option>Service(Phục vụ)</option>
          </select>
        </div>
        <div class="location">
          <select>
            <option>Nơi làm việc</option>
            <option>Pizza 4P's Ho Chi Minh</option>
            <option>Pizza 4P's Binh Duong</option>
            <option>Pizza 4P's Ha Noi</option>
          </select>
        </div>
        <div class="button">Tìm kiếm</div>
      </div>
    </div>

    <div id="alljobs" class="career-category">
      <div class="header">
        <h2>Jobs in Pizza 4P’s</h2>
      </div>

      <div class="list-job">
        <div class="item">
          <div class="wrap">
            <h3 class="title">
              <a
                href="https://pizza4ps.talent.vn/job/hcm-admin-executive-bo-phan-me-31655"
                >[HCM] Admin Executive - Bộ phận M&E</a
              >
            </h3>
            <div class="infor">
              <a href="https://pizza4ps.talent.vn/jobs?dept=1935"
                >Head Office (Non-managerial Level)</a
              >
              <span class="dot">.</span>
              <a href="https://pizza4ps.talent.vn/jobs?office=3612"
                >Pizza 4P‘s Ho Chi Minh</a
              >
            </div>
            <div class="infor">
              <span>Toàn thời gian</span>
              <span class="dot">.</span>
              <span>10,000,000 - 12,000,000 VNĐ</span>
            </div>
          </div>

          <div class="button">
            <a
              href="https://pizza4ps.talent.vn/job/hcm-admin-executive-bo-phan-me-31655?apply=1"
              >Apply now</a
            >
          </div>
        </div>
        <div class="item">
          <div class="wrap">
            <h3 class="title">
              <a
                href="https://pizza4ps.talent.vn/job/hcm-admin-executive-bo-phan-me-31655"
                >[HCM] Admin Executive - Bộ phận M&E</a
              >
            </h3>
            <div class="infor">
              <a href="https://pizza4ps.talent.vn/jobs?dept=1935"
                >Head Office (Non-managerial Level)</a
              >
              <span class="dot">.</span>
              <a href="https://pizza4ps.talent.vn/jobs?office=3612"
                >Pizza 4P‘s Ho Chi Minh</a
              >
            </div>
            <div class="infor">
              <span>Toàn thời gian</span>
              <span class="dot">.</span>
              <span>10,000,000 - 12,000,000 VNĐ</span>
            </div>
          </div>

          <div class="button">
            <a
              href="https://pizza4ps.talent.vn/job/hcm-admin-executive-bo-phan-me-31655?apply=1"
              >Apply now</a
            >
          </div>
        </div>
      </div>

      <div class="load-more">Xem thêm</div>
    </div>

    <div id="benefits" class="career-benefits">
      <div class="header">
        <h2>HOW WE DELIVER “WOW” & SHARE HAPPINESS</h2>
        <p>
          “Our goal is to gain “10 MILLION SMILES” in 2023 and we’ll not be able
          to achieve this goal without YOU. Your great energy and big smiles are
          what contributed to spread Happiness to more people in all over the
          World” – Yosuke Masuko (CEO of 4P’s Corporation)
        </p>
      </div>

      <div class="benefit">
        <div class="wrap">
          <div class="content">
            <div class="icon">
              <img
                src="https://datax-talent.basecdn.net/pizza4p/icons/best-employers-toronto-badge.svg"
                alt=""
              />
            </div>
            <div class="title">
              <h4>Open & Friendly Environment</h4>
              <p>
                Not just colleagues, we are more like members in a big Family.
                Bringing you a happy smile is what we aim at.
              </p>
            </div>
          </div>
          <div class="content">
            <div class="icon">
              <img
                src="https://datax-talent.basecdn.net/pizza4p/icons/development-toronto-bank.svg"
                alt=""
              />
            </div>
            <div class="title">
              <h4>Career Development Opportunities</h4>
              <p>
                We provide the most thorough & dedicated training programs, with
                the desire not only to improve professional skills, but also to
                train sustainable skills for members in different positions.
                With 4P’s current rapid growth, careers developments are always
                promising for those deserved.
              </p>
            </div>
          </div>
          <div class="content">
            <div class="icon">
              <img
                src="https://datax-talent.basecdn.net/pizza4p/icons/employer-award.svg"
                alt=""
              />
            </div>
            <div class="title">
              <h4>Long list of attractive Benefits</h4>
              <p>
                PVI Healthcare package, Internal discounts program, Competitive
                salary, Attractive bonus, Monthly team building parties, etc.,
                and many other exciting perks only for 4P’s members are waiting
                for you to discover yourself.
              </p>
            </div>
          </div>
          <div class="content">
            <div class="icon">
              <img
                src="https://datax-talent.basecdn.net/pizza4p/icons/employer-award.svg"
                alt=""
              />
            </div>
            <div class="title">
              <h4>Kaizen (Continuous Improvement)</h4>
              <p>
                We are driven to surpass what has already been achieved. We take
                actions towards change and improvement. We celebrate failures
                and value experimenting. We encourage and appreciate new ideas
                to improve the quality of work.
              </p>
            </div>
          </div>
        </div>

        <div class="image">
          <img
            src="https://datax-talent.basecdn.net/pizza4p/benefits.jpg"
            alt=""
          />
        </div>
      </div>
    </div>

    <div class="career-footer">
      <div class="logo">
        <img
          src="https://datax-talent.basecdn.net/pizza4p/logo-footer.png"
          alt=""
        />
      </div>
      <div class="social"><a href="#">Follow us Facebook</a></div>
      <div class="infor">
        Hotline HR: <a href="tel:078 388 4977">078 388 4977</a>
        <br />
        Website:
        <a href="https://pizza4ps.com/" target="_blank"
          >https://pizza4ps.com/</a
        >
      </div>
      <div class="copyright">
        ©2019 <a href="https://pizza4ps.com/" target="_blank">Pizza 4P's.</a>
        <br />
        Powered by
        <a
          href="https://base.vn/hiring?utm_source=https://pizza4ps.talent.vn"
          target="_bank"
          >Base E-Hiring.</a
        >
      </div>
    </div>
  </div>
</template>

<script>
import CarouselParent from '@/components/slider-show/carousel-parent.vue'

export default {
  components: { CarouselParent },
  layout: 'empty',
  data() {
    return {
      slides: [
        'https://datax-talent.basecdn.net/pizza4p/banner/image-cover2.jpg',
        'https://datax-talent.basecdn.net/pizza4p/banner/image-cover3.jpg',
        'https://datax-talent.basecdn.net/pizza4p/banner/image-cover4.jpg',
      ],
    }
  },
}
</script>

<style lang="scss" scoped>
.career-header {
  width: 100%;
  color: #fff;
  padding: 16px;
  background-color: #324252;
  display: flex;

  > .logo {
    margin-left: 100px;
  }

  > .logo > img {
    width: 45px;
    height: 100%;
  }
}

.list {
  display: flex;
  list-style: none;
  margin-left: 26px;

  > .item {
    padding: 10px 16px;
  }

  > .item > a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
  }
}

.career-slider {
  position: relative;
  width: 100%;
  height: 330px;

  > .search {
    display: flex;
    position: absolute;
    top: 70%;
    left: 14%;
    background-color: #324252;
    padding: 20px;
    color: #000;
  }

  > .search > .text,
  .service > select,
  .location > select {
    background-color: #fff;
    width: 240px;
    height: 36px;
    padding: 5px 15px;
    outline: none;
    border-style: none;
    margin: 0 16px;
  }

  > .search > .button {
    color: #fff;
    cursor: pointer;
    font-weight: bold;
    padding: 5px 15px;
    margin: 0 16px;
    background-color: #f7941d;
    height: 35px;
    text-transform: uppercase;
    font-family: 'Century Book';
  }

  > .search > .button:hover {
    background-color: #02499d;
  }
}

.career-category {
  width: 100%;
  padding-top: 160px;
  background-color: #111;

  > .header {
    text-align: center;
    margin-bottom: 20px;
    padding-bottom: 20px;

    > h2 {
      margin-bottom: 10px;
      font-size: 55px;
      font-weight: 300;
      color: #fff;
      font-family: 'Century Book';
    }
  }

  .list-job {
    box-sizing: border-box;
    width: 100%;
    position: relative;
    max-width: 1100px;
    margin: 0px auto;

    > .item {
      display: flex;
      justify-content: space-between;
      width: 100%;
      padding: 15px 10px 15px 15px;
      color: #fff;
      border: 1px dashed #eee;
      box-sizing: border-box;
      border-radius: 5px;
      margin-bottom: 30px;
    }
  }

  > .list-job > .item > .wrap {
    > .title {
      margin-bottom: 10px;
      font-size: 24px;
      line-height: 24px;

      > a {
        text-decoration: none;
        color: #f4f2ef;
        font-size: 24px;
        font-family: 'Century Book';
      }

      > a:hover {
        text-decoration-line: underline;
      }
    }

    > .infor {
      font-size: 16px;
      color: #ddd6c5;
      margin-bottom: 10px;
      font-family: 'Century Book';

      > a {
        text-decoration: none;
        color: #ddd6c5;
        font-size: 16px;
      }

      > a:hover {
        text-decoration-line: underline;
      }

      > .dot {
        margin: 4px;
      }
    }
  }

  > .list-job > .item > .button {
    background-color: #02499d;
    margin: 8px;
    padding: 6px;
    height: 40px;
    border-radius: 3px;

    > a {
      color: #fff;
      padding: 16px;
      text-decoration: none;
      font-size: 18px;
      font-family: 'Century Book';
    }
  }

  .load-more {
    padding: 15px;
    color: #f4f2ef;
    border: 2px solid #f4f2ef;
    cursor: pointer;
    text-align: center;
    max-width: 150px;
    margin: 0px auto;
    border-radius: 0px;
    font-family: 'Century Book';
  }
}

.career-benefits {
  box-sizing: border-box;
  width: 100%;
  position: relative;
  margin: 0px auto;
  padding-top: 120px;
  background-color: #111;

  .header {
    color: #f4f2ef;
    padding: 0 140px;
    text-align: center;
    margin-bottom: 40px;

    > h2 {
      font-size: 50px;
      color: #f4f2ef;
      text-align: center;
      margin-bottom: 40px;
    }

    > p {
      font-size: 19px;
      line-height: 30px;
      font-family: 'Century Book';
    }
  }

  .benefit {
    padding: 20px 140px 20px 140px;
    display: flex;

    > .wrap > .content {
      padding: 6px 0;
      display: flex;
      color: #f4f2ef;

      > .icon > img {
        width: 50px;
        height: 76px;
      }

      .title {
        margin-left: 20px;

        > h4 {
          font-family: 'Century Book';
          font-size: 20px;
          margin-bottom: 10px;
        }

        > p {
          font-family: 'Century Book';
          font-size: 14px;
          line-height: 22px;
        }
      }
    }

    > .image {
      margin-left: 40px;
      > img {
        width: 550px;
        height: 550px;
      }
    }
  }
}

.career-footer {
  padding: 26px 0px;
  color: #f4f2ef;
  background-color: #324252;
  display: flex;
  justify-content: space-around;
  align-items: center;

  > .logo > img {
    width: 60px;
    height: 60px;
  }

  > .social > a,
  > .infor > a,
  > .copyright > a {
    color: #f4f2ef;
    text-decoration: none;
  }
}
</style>
