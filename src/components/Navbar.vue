<template>
  <nav>
      <a href=""><p>Outdoor Vibrations</p></a>
      <ul>
          <a href=""><li>Home</li></a>
          <a href=""><li>About</li></a>
          <a href=""><li>Blog</li></a>
      </ul>
      <a href=""><p>Subscribe</p></a>
  </nav>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>
    * {
        text-decoration: none;
    }

    nav {
        display: flex;
        justify-content: space-evenly;
    }

    ul {
        display: flex;
    }

    li {
        margin-left: 42px;
        list-style: none;
    }
</style>