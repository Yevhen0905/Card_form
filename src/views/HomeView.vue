<template>
  <div class="home">
    <CreditCard/>
  </div>
</template>

<script>
import CreditCard from '@/components/CreditCard/CreditCard.vue';
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
    CreditCard
  }
}
</script>
