<template>
<footer>
  <section class="bg-wrapper">
      <ul>
          <li>
                <h3>dc comics</h3>
          </li>
          <li>
              <a href="#">
                    <p>Characters</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Comics</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Movies</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>TV</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Games</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>videos</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>News</p>
              </a>
          </li>
      </ul>
      <ul>
          <li>
                <h3>shop</h3>
          </li>
          <li>
              <a href="#">
                    <p>Shop DC</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Shop DC collectibles</p>
              </a>
          </li>
      </ul>
      <ul>
          <li>
                <h3>sities</h3>
          </li>
          <li>
              <a href="#">
                    <p>DC</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>MAD Magazine</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>DC Kids</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>DC Universe</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>DC Power Visa</p>
              </a>
          </li>
      </ul>
      <ul>
          <li>
                <h3>dc</h3>
          </li>
          <li>
              <a href="#">
                    <p>Term of Use</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Privacy policy (New)</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Ad choices</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Advertising</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Jobs</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Subscriptions</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Talent Workshops</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>CPSC Certificates</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Rating</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Shop Help</p>
              </a>
          </li>
          <li>
              <a href="#">
                    <p>Contact Us</p>
              </a>
          </li>
      </ul>
  </section>
    <div class="footer-banner">
        <div class="wrapper-footer-banner">
        <div class="nav-left">
            <a class="btn">sign-up now!</a>
        </div>
        <div class="nav-right">
            <div>
                <h3>follow us</h3>
            </div>
            <div>
                <ul>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-facebook.png" alt="facebook">
                        </a>
                        <a href="#">
                            <img src="../assets/img/footer-periscope.png" alt="periscope">
                        </a>
                        <a href="#">
                            <img src="../assets/img/footer-pinterest.png" alt="pinterest">
                        </a>
                        <a href="#">
                            <img src="../assets/img/footer-twitter.png" alt="twitter">
                        </a>
                        <a href="#">
                            <img src="../assets/img/footer-youtube.png" alt="youtube">
                        </a>
                    </li>
                </ul>
            </div>
        </div>
        </div>
    </div>
</footer>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style lang="scss" scoped>
@import '../style/variables.scss';
    .bg-wrapper {
    width: 80%;
    padding: 15px 10px 15px 10px;
    margin: auto;
    background-image: url(../assets/img/dc-logo-bg.png);
    background-position: right;
    background-repeat: no-repeat;
    background-size: 48%;
    }
    footer {
        background-image: url(../assets/img/footer-bg.jpg);
        background-size: cover;
        background-repeat: no-repeat;
    }
    section {
        display: flex;
        ul {
            flex-direction: column;
            list-style: none;
            margin-right: 20px;
        }
        li {
            padding-bottom: 5px;
        }
        a {
            text-decoration: none;
            color: $text-footer-grey;
        }
        a:hover {
            color: $background-text-lightblue;
        }
        ul li:first-child {
            padding: 10px 0 15px 0;
            h3 {
                text-transform: uppercase;
                color: $textcolorwhite;
            }
        }
    }
    .footer-banner {
        background-color: $background-darkgrey;
        .wrapper-footer-banner {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 80%;
            padding: 15px 10px 15px 10px;
            margin: auto;
        }
        .btn {
            padding: 12px 12px;
            border: 1px solid $background-text-lightblue;
            color: white;
            text-transform: uppercase;
            background-color: #303030;
            cursor: pointer;
        }
        .btn:hover {
            background-color: $background-text-lightblue;
        }
    }
    .nav-right {
        display: flex;
        justify-content: space-between;
        align-items: center;
        h3 {
            margin-right: 15px;
            text-transform: uppercase;
            color: $background-text-lightblue;
        }
        ul li {
            list-style: none;
            a {
                padding: 10px 10px;
            }
        }
    }
</style>