<template>
  <header>
    <HeaderBar />
  </header>

  <main>
    <TotalBalance />
    <IncomeExpense />
    <TransactionList :transactions="transactions" />
    <AddTransaction />
  </main>
</template>


<script setup>
import HeaderBar from './components/HeaderBar.vue';
import TotalBalance from './components/TotalBalance.vue'
import IncomeExpense from './components/IncomeExpense.vue';
import TransactionList from './components/TransactionList.vue';
import AddTransaction from "./components/AddTransaction.vue"

import { ref } from 'vue';

const transactions = ref(
  [
    { id: 1, text: "Flower", amount: -19 },
    { id: 1, text: "Salary", amount: 500 },
  ]
)
</script>