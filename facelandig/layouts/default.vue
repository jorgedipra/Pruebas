<template>
 <v-app >
    <v-app-bar
      :clipped-left="clipped"
      fixed
      app >
    
      <v-toolbar-title v-text="title" />
      <v-spacer />
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      title: 'jorge'
    }
  }
}
</script>
