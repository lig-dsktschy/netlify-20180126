<template>
  <div>
    <header>
      <nav>
        <nuxt-link to="/">Top</nuxt-link>
        <nuxt-link to="/news">News</nuxt-link>
        <nuxt-link to="/about">About</nuxt-link>
        <nuxt-link to="/service">Service</nuxt-link>
        <nuxt-link to="/contact">Contact</nuxt-link>
      </nav>
    </header>
    <main>
      <h1>News</h1>
    </main>
    <footer>
      <small>&copy; 2017 LOREM IPSUM</small>
    </footer>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'News | LOREM IPSUM'
    }
  }
}
</script>

<style scoped>
</style>
