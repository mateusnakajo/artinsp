<template>
  <div>
  <v-container grid-list-xl text-xs-center>
    <v-layout row wrap >
      <v-flex xs12>
        <v-card class="elevation-5">
        <v-img src="../img/avenida-paulista.jpg" aspect-ratio="2.0" height="400px" >
        </v-img>
        <v-card-title class="text-sm-left">
          <p>
          A cada canto uma sensação nova, a cada esquina uma arte nova. 
          Nós acreditamos que toda arte tem seu valor e aqui encontra-se de tudo um pouco. 
          Indicações de roles, poesias, resenhas de filme e livro. Qual é a sua arte preferida?
          </p>
        </v-card-title>
        </v-card>
      </v-flex>
    </v-layout>

    <v-layout row wrap mt-3>

      <v-flex xs4>
        <v-card class="elevation-5">

         <v-img src="../img/livro1.png" aspect-ratio="0.5" height="300px"> </v-img>
        <v-card-title class="text-sm-left">
          <h3 class="headline mb-0">Coração Satânico - Resenha</h3>
          <p v-dummy="30">...</p>
          <a>Leia mais</a>
        </v-card-title>
        </v-card>
      </v-flex>

      <v-flex xs4>
        <v-card class="elevation-5">
         <v-img src="../img/pulp-fiction.jpg" aspect-ratio="0.5" height="300px"> </v-img>
        <v-card-title class="text-sm-left">
          <h3 class="headline mb-0">Pulp Fiction - Resenha</h3>
          <p v-dummy="30">...</p>
          <a>Leia mais</a>
        </v-card-title>
        </v-card>
      </v-flex>
        
      <v-flex xs4>
        <v-card class="elevation-5">
         <v-img src="../img/sao-paulo.jpg" aspect-ratio="0.5" height="300px"> </v-img>
        <v-card-title class="text-sm-left">
          <h3 class="headline mb-0">Cidade Querida</h3>
          <p v-dummy="30">...</p>
          <a>Leia mais</a>
        </v-card-title>
        </v-card>
      </v-flex>
      <v-flex align-content-center>
        <v-btn color="success">Ver mais</v-btn>
      </v-flex>
    </v-layout>
  </v-container>
  <v-container fluid class="blue-grey lighten-5">
    <v-container>
    <v-layout row>
      <v-flex xs8 class="pr-3">
        <v1-image height="200px"/>
      </v-flex>
      <v-flex xs4 class="pl-2" >
        <v1-image height="200px"/>
      </v-flex>
    </v-layout>
    </v-container>
  </v-container>
  </div>
</template>