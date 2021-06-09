<template>
    <main>
        <section class="jumbotron">
        </section>
        <section class="main-container">
        <div class="wrapper">
            <div class="sticker">CURRENT SERIES</div>
            <div class="item-container">
                <Card :comics="comic" v-for="(comic,index) in comics" :key="index"/>
            </div>
            <div class="button">
                <a href="#">LOAD MORE</a>
            </div>
        </div>
        </section>
        <section class="shop">
            <div class="wrapper shop-item">
                <article>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="buy-digital">
                <p>digital comics</p>
                </article>
                <article>
                <img src="../assets/img/buy-comics-merchandise.png" alt="merchadinse">
                <p>dc merchandise</p>
                </article>
                <article>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="shop-locator">
                <p>subscriptions</p>
                </article>
                <article>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
                <p>comic shop locator</p>
                </article>
                <article>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="visa">
                <p>dc power visa</p>
                </article>
            </div>
        </section>
    </main>
</template>

<script>
import Card from '../components/Card';
import comics from '../data/dc-comics.json';
export default {
    name: 'Main',
    components: {
    Card
  },
  data () {
    return {
      comics,
    }
  }
}
</script>

<style lang="scss" scoped>
@import '../style/variables.scss';
    .wrapper {
    width: 80%;
    padding: 30px 20px;
    margin: auto;
    }
    .jumbotron {
        height: 300px;
        color: white;
        background-image: url(../assets/img/jumbotron.jpg);
        background-size: cover;
        background-repeat: no-repeat;
    }
    .main-container {
        position: relative;
        background-color: black;
    }
    .sticker {
        position: absolute;
        top: -20px;
        font-weight: bold;
        padding: 10px 10px;
        color: white;
        background-color: $background-text-lightblue;
    }
    .item-container {
        display: flex;
        flex-wrap: wrap;
        padding: 10px 0px;
    }
        .button {
            display: flex;
            justify-content: center;
            a {
            padding: 10px 80px;
            font-weight: bold;
            text-decoration: none;
            color: white;
            background-color: $background-text-lightblue;
            }
        }
    .shop {
        display: flex;
        align-items: center;
        width: 100%; 
        background-color: $background-text-lightblue;
        article {
            display: flex;
            align-items: center;
            padding: 10px 0 10px 0;
            cursor: pointer;
            img {
                margin-right: 15px;
            }
            p {
                font-size: 12px;
                text-transform: uppercase;
                color: white;
            }
        }
        img {
            height: 50px;
        }
        .shop-item {
            display: flex;
            justify-content: space-between;
        }
    }
</style>