<template>
  <header>
    <HeaderBar />
  </header>

  <main>
    <TotalBalance />
    <IncomeExpense />
  </main>
</template>


<script>
import HeaderBar from './components/HeaderBar.vue';
import TotalBalance from './components/TotalBalance.vue'
import IncomeExpense from './components/IncomeExpense.vue';

export default {
  components: {
    HeaderBar,
    TotalBalance,
    IncomeExpense
  }
}
</script>