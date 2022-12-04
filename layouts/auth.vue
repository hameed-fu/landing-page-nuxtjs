<template>
  <v-app light>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'default',
  props: {
    error: {
      type: Object,
      default: null
    }
  },
  data() {
    return {
    }
  }
}
</script>

<style scoped>
h1 {
  font-size: 20px;
}
</style>
