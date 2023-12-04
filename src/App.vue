<template>
  <header>
    <HeaderBar />
  </header>

  <main>
    <TotalBalance />
    <IncomeExpense />
    <TransactionList />
    <AddTransaction />
  </main>
</template>


<script setup>
import HeaderBar from './components/HeaderBar.vue';
import TotalBalance from './components/TotalBalance.vue'
import IncomeExpense from './components/IncomeExpense.vue';
import TransactionList from './components/TransactionList.vue';
import AddTransaction from "./components/AddTransaction.vue"
</script>