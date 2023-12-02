<template>
  <header>
    <HeaderBar />
  </header>

  <main>
    <TotalBalance />
  </main>
</template>


<script>
import HeaderBar from './components/HeaderBar.vue';
import TotalBalance from './components/TotalBalance.vue'

export default {
  components: {
    HeaderBar,
    TotalBalance
  }
}
</script>