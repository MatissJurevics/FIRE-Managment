<script lang="ts">
export default {};
</script>

<template>
  <nav>

    <v-app-bar
      absolute
      color="#CF1259"
      dark

    >




      <v-app-bar-title>Title</v-app-bar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>
            <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <template v-slot:extension>
        <v-tabs align-with-title>
          <v-tab>Summary</v-tab>
          <v-tab>Budgets</v-tab>
          <v-tab>Expenditure</v-tab>
          <v-tab>Investments</v-tab>
          <v-tab>Calculators</v-tab>
        </v-tabs>
      </template>
    </v-app-bar>

  </nav>
</template>
