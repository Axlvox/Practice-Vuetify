<template>
  <v-app theme="light">
    <v-app-bar flat color="#5F4BB6" class="border-b" title="App">
    </v-app-bar>
    <v-navigation-drawer>
    </v-navigation-drawer>
    <v-main>
   <v-container>
    <div class="d-flex justify-space-around">
      <div class="pa-4 border rounded-lg elevation-2 text-center" style="width: 100px">Box 1</div>
      <div class="pa-4 border rounded-lg elevation-2 text-center" style="width: 100px">Box 2</div>
      <div class="pa-4 border rounded-lg elevation-2 text-center" style="width: 100px">Box 3</div>
    </div>
   </v-container>
    </v-main>

    <AppFooter />
  </v-app>
</template>

<script setup>
  //
</script>
