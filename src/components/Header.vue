<template>
    <header class="wrapper">
      <nav>
          <div>
          <img src="../assets/img/dc-logo.png" alt="logo">
          </div>
          <div class="nav-right">
          <ul>
              <li v-for="(link, index) in links" :key="index">
                  <a :href="link.href">{{link.text}}</a>
              </li>
          </ul>
          </div>
      </nav>
  </header>
</template>

<script>
export default {
    name: 'Header',
    data () {
        return {
            links: [
                {
                    text: "characters",
                    href: "link",
                    active: false,
                },
                {
                    text: "comics",
                    href: "link",
                    active: false,
                },
                {
                    text: "movies",
                    href: "link",
                    active: false,
                },
                {
                    text: "tv",
                    href: "link",
                    active: false,
                },
                {
                    text: "games",
                    href: "link",
                    active: false,
                },
                {
                    text: "collectibles",
                    href: "link",
                    active: false,
                },
                {
                    text: "videos",
                    href: "link",
                    active: false,
                },
                {
                    text: "fans",
                    href: "link",
                    active: false,
                },
                {
                    text: "news",
                    href: "link",
                    active: false,
                },
                {
                    text: "shop",
                    href: "link",
                    active: false,
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
    .wrapper {
    width: 80%;
    margin: auto;
    padding: 10px 0;
    }
    nav {
        display: flex;
        justify-content: space-between;
        width: 100%;
        background-color: white;
        img {
            width: 50px;
        }
        .nav-right {
            display: flex;
            align-items: center;
        }
    }
    ul {
        display: flex;
        align-items: flex-end;
        align-items: center;
        list-style: none;
        li {
            padding: 0 10px;
        }
        li a {
            font-size: 12px;
            text-decoration: none;
            text-transform: uppercase;
            padding: 25px 0;
            color: black;
        }
        & a:hover {
            color: #0282F9;
            border-bottom: 3px solid #0282F9;
        }
    }
</style>