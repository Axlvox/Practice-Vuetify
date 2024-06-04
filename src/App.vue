<template>
  <v-app theme="light">
    <v-app-bar flat color="#5F4BB6" class="border-b">
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-app-title>Menu</v-app-title>
      <v-avatar>
          <v-img 
          class="" 
          cover 
          src="https://www.creativefabrica.com/wp-content/uploads/2021/03/10/Women-avatar-icon-Graphics-9452550-1-580x386.jpg"></v-img>
        </v-avatar>
    </v-app-bar>
    <v-navigation-drawer>
    </v-navigation-drawer>
    <v-main>
   <v-container>
    <h1>Dashboard</h1>

   <v-row>
    <v-col cols="12" md="4" lg="3">
        <v-card>
          <v-img 
          class="align-end text-white" 
          src=https://media.tacdn.com/media/attractions-splice-spp-674x446/0c/04/55/9b.jpg>
            <v-card-title>Foto</v-card-title>
          </v-img>
          <v-card-subtitle class="pt-3">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolorem architecto quam sit voluptas explicabo maxime obcaecati aperiam vero?</v-card-subtitle>
          <v-card-text class="text-center">
            <div>Texto da Imagem</div>
            <div>Descrição</div>
          </v-card-text>
          <v-card-actions class="justify-center px-10">
            <v-btn text class="align-center text-purple bg-blue-grey-lighten-4" style="width:60%">Botão</v-btn>
            <v-btn append-icon="mdi-heart" text class="text-red bg-red-lighten-5">FAVORITAR</v-btn>
          </v-card-actions>
        </v-card>
        
    </v-col>
   </v-row>
   </v-container>
    </v-main>

    <AppFooter />
  </v-app>
</template>

<script setup>
  //
</script>
