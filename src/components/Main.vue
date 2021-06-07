<template>
    <main>
        <section class="wrapper">
            <article>
                <h2> --> Content goes here </h2>
            </article>
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
export default {
    name: 'Main',
}
</script>

<style lang="scss" scoped>
    .wrapper {
    width: 80%;
    padding: 10px;
    margin: auto;
    }
    main {
        width: 100%;
        height: 200px;
        color: white;
        background-color: #1D1D1D;
        .shop {
            display: flex;
            align-items: center;
            width: 100%;
            height: 100px;   
            background-color: #0282F9;
            article {
                display: flex;
                justify-content: space-between;
                img {
                    margin-right: 15px;
                }
                p {
                    font-size: 12px;
                    text-transform: uppercase;
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
    }
</style>