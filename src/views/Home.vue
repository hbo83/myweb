<template>
  <div class="home">
    <Header />
    <About />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header';

export default {
  name: 'home',
  components: {
    Header
  }
}
</script>
