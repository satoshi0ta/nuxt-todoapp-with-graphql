<template>
  <v-app>
    <v-toolbar fixed>
      <v-toolbar-title v-text="title" />
    </v-toolbar>
    <v-content>
      <nuxt />
    </v-content>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      title: 'TodoApp',
    }
  },
}
</script>
