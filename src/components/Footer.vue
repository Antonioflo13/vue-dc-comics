<template>
<footer>
  <section class="bg-wrapper">
      <ul>
          <li>
              <h3>DC COMICS</h3>
              <p>Characters</p>
              <p>Comics</p>
              <p>Movies</p>
              <p>TV</p>
              <p>Games</p>
              <p>videos</p>
              <p>News</p>
          </li>
          <li>
              <h3>DC COMICS</h3>
              <p>Characters</p>
              <p>Comics</p>
              <p>Movies</p>
              <p>TV</p>
              <p>Games</p>
              <p>videos</p>
              <p>News</p>
          </li>
      </ul>
      <ul>
          <li>
              <h3>DC COMICS</h3>
              <p>Characters</p>
              <p>Comics</p>
              <p>Movies</p>
              <p>TV</p>
              <p>Games</p>
              <p>videos</p>
              <p>News</p>
          </li>
          <li>
              <h3>DC COMICS</h3>
              <p>Characters</p>
              <p>Comics</p>
              <p>Movies</p>
              <p>TV</p>
              <p>Games</p>
              <p>videos</p>
              <p>News</p>
          </li>
      </ul>
      <ul>
          <li>
              <h3>DC COMICS</h3>
              <p>Characters</p>
              <p>Comics</p>
              <p>Movies</p>
              <p>TV</p>
              <p>Games</p>
              <p>videos</p>
              <p>News</p>
          </li>
      </ul>
  </section>
    <div class="footer-fixed">
        <div class="wrapper-footer-fixed">
        <div class="nav-left">
            <button>sign-up now!</button>
        </div>
        <div class="nav-right">
            <div>
                <h3>follow us</h3>
            </div>
            <div>
                <ul>
                    <li>
                        <a href=""></a>
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
    .bg-wrapper {
    width: 80%;
    padding: 10px;
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
            color: white;
        }
        ul li {
            padding: 10px 0 20px 0;
        }
        ul li:first-child {
            padding: 10px 0 20px 0;
        }
    }
    .wrapper-footer-fixed {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 80%;
        padding: 10px;
        margin: auto;
    }
    .footer-fixed {
        background-color: #303030;
    }
</style>