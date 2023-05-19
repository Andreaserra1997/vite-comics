<script>
export default {
  data() {
    return {
      linkDC: [
        {
          name: "CHARACTERS",
          src: "#",
        },
        {
          name: "COMICS",
          src: "#",
        },
        {
          name: "MOVIES",
          src: "#",
        },
        {
          name: "TV",
          src: "#",
        },
        {
          name: "GAMES",
          src: "#",
        },
        {
          name: "COLLECTIBLES",
          src: "#",
        },
        {
          name: "VIDEOS",
          src: "#",
        },
        {
          name: "FANS",
          src: "#",
        },
        {
          name: "NEWS",
          src: "#",
        },
        {
          name: "SHOP",
          src: "#",
        },
      ],
    };
  },
};
</script>

<template>
  <ul>
    <li v-for="linkItem in linkDC" :key="linkItem.name">
      <a :href="linkItem.src">{{ linkItem.name }}</a>
    </li>
  </ul>
</template>

<style lang="scss" scoped>
ul {
  display: flex;
  li {
    list-style: none;
    padding-inline: 0.6rem;
    a {
      text-decoration: none;
      color: black;
    }
  }
}
</style>
