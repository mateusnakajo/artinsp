<template>
  <v-container grid-list-xl text-xs-center>
    <v-layout row wrap>
      <v-flex xs10 offset-xs1>
        <v-card color="purple">
          <v-card-text>xs10 offset-xs1</v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs7 offset-xs5 offset-md2 offset-lg5>
        <v-card color="secondary">
          <v-card-text>xs7 offset-(xs5 | md2 | lg5)</v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs12 sm5 md3>
        <v-card color="primary">
          <v-card-text>(xs12 | sm5 | md3)</v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs12 sm5 md5 offset-xs0 offset-lg2>
        <v-card color="green">
          <v-card-text>(xs12 | sm5 | md5) offset-(xs0 | lg2)</v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>