<template>
  <v-app-bar color="transparent" flat scroll-behavior="hide">
    <v-app-bar-title class="text-orange-darken-3">
        FOODEAT
    </v-app-bar-title>
    <v-spacer></v-spacer>
    <v-tabs bg-color="transparent" color="#9b7150" fixed-tabs>
        <v-tab text="HOME"></v-tab>
        <v-tab text="MENU"></v-tab>
        <v-tab text="ABOUT"></v-tab>
    </v-tabs>
    <v-avatar size="36px">
        <v-img src="https://avatars0.githubusercontent.com/u/9064066?v=4&s=460"></v-img>
    </v-avatar>
    <v-icon class="ml-2" icon="mdi mdi-chevron-down" variant="text"></v-icon>
  </v-app-bar>
</template>

<script>
export default {

}
</script>

<style>

</style>