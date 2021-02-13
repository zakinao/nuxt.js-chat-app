<template>
  <main class="container relative min-h-screen pt-16">
    <Header />
    <Nuxt />
  </main>
</template>

<script>
import Header from '~/components/Header'

export default {
  components : {
    Header
  }
}
</script>
