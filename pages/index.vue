<template>
  <v-container class="index">
    <card
      v-for="i in 5"
      :key="i"
    />
  </v-container>
</template>

<script>
import Card from '~/components/card.vue'

export default {
  components: {
    Card
  }
}
</script>