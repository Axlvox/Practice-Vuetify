<template>
  <v-app theme="light">
    <v-app-bar flat color="#5F4BB6" class="border-b" title="App">
    </v-app-bar>
    <v-navigation-drawer permanent>
    </v-navigation-drawer>
    <v-main>
   <v-container>
    <div class="d-flex justify-space-between">
     <div class="w-100 pa-4 border rounded-lg -elevation-2 text-center">Box 1
    </div>
    <div class="w-100 pa-4 border rounded-lg -elevation-2 text-center">Box 2
    </div>
    <div class="w-100 pa-4 border rounded-lg -elevation-2 text-center">Box 3
    </div>
    </div>
   </v-container>
    </v-main>

    <AppFooter />
  </v-app>
</template>

<script setup>
  //
</script>
