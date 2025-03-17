<template>
  <div>
    <h4>Your Balance</h4>
    <h1 id="balance">${{ balance }}</h1>
  </div>
</template>

<script lang="ts" setup>
import { ref, computed } from 'vue'

// const balance = computed(() => props.totalIncome - props.totalExpense)

const props = defineProps({
  transactions: Array as PropType<Transaction[]>,
})
</script>
