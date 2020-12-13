<template>
  <v-card class="card mb-5">
    <nuxt-link
      :to="{ name: 'blog-slug'}"
      class="wrapper"
    >
      <v-card-title>記事タイトル</v-card-title>
    <v-card-text>
      <v-row
        align="center"
        class="mx-0"
      >
      </v-row>
      <div>記事の概要</div>
    </v-card-text>
    </nuxt-link>
  </v-card>
</template>

<style lang="scss" scoped>
.wrapper {
  text-decoration: none;
}
</style>