<template>
  <header>
      <nav>
          <a href="#">
              <img src="../assets/img/dc-logo.png" alt="">
          </a>
          <ul>
              <li v-for="(link, index) in links" :key="index">
                  {{ link.text }}
              </li>
          </ul>
      </nav>
  </header>
</template>

<script>
export default {
    name: "Header",
    data: function() {
        return {
            links: [
                {
                    text: "characters",
                    url: "characters",
                    select: false
                },
                {
                    text: "characters",
                    url: "characters",
                    select: false
                },
                {
                    text: "characters",
                    url: "characters",
                    select: false
                },
                {
                    text: "characters",
                    url: "characters",
                    select: false
                },
                {
                    text: "characters",
                    url: "characters",
                    select: false
                },
                {
                    text: "characters",
                    url: "characters",
                    select: false
                },
                {
                    text: "characters",
                    url: "characters",
                    select: false
                },
                {
                    text: "characters",
                    url: "characters",
                    select: false
                },
                {
                    text: "characters",
                    url: "characters",
                    select: false
                },
                {
                    text: "characters",
                    url: "characters",
                    select: false
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
    nav {
        width: 100%;
        height: 8vh;
        display: flex;
        align-content: center;
        align-items: center;
        justify-content: space-around;;
        text-transform: uppercase;
        font-size: 10px;

        img {
            height: 85%;
        }
    }
    ul {
        display: flex;
        align-items: center;

        li {
            padding: 10px;
            list-style: none;

            &:hover {
                cursor: pointer;
            }
        }
    }

    nav > a {
            height: 80%;
        }
</style>