<template>
  <div>
    <v-toolbar color="blue-grey-lighten-4" dark>
      <div><a href="https://mb.mahidol.ac.th/app/#/"></a></div>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Vuetify</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-export</v-icon>
      </v-btn>
    </v-toolbar>
  </div>
  <router-view />
</template>