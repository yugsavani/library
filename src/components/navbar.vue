<template>
    <div>
        <v-app-bar
     app dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="@/assets/logo.png"
          transition="scale-transition"
          width="40"
         
        />

        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        />
        <label> {{$const.APP_NAME}}</label>
      </div>

      <v-spacer></v-spacer>

      <v-btn text>
        Login
      </v-btn>
      <v-icon>mdi-account-circle</v-icon>
    </v-app-bar>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>