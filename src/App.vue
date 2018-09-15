<template>
  <v-app>
     <v-toolbar dark>
    <v-toolbar-title>Art in SP</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn flat>Textos</v-btn>
      <v-btn flat>Fotos</v-btn>
      <v-btn flat>Contato</v-btn>
    </v-toolbar-items>
  </v-toolbar>
    <v-content>
      <router-view></router-view>
    </v-content>
    <v-footer class="pa-3 grey darken-3">
      <v-spacer></v-spacer>
      <div>&copy; {{ new Date().getFullYear() }}</div>
    </v-footer></v-app>
</template>
