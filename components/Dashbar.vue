<script lang="ts">
export default {};
</script>

<template>
  <nav>
    <v-app-bar color="#CF1259" class="px-8" dense dark>
      <v-app-bar-title class="text-no-wrap">FI/RE Dashboard</v-app-bar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <template v-slot:extension>
        <v-tabs align-with-title>
          <v-tab to="/dashboard" nuxt>Summary</v-tab>
          <v-tab to="/dashboard/budget" nuxt>Budgets</v-tab>
          <v-tab to="/dashboard/cashflow" nuxt>Cash-Flow</v-tab>
          <v-tab to="/dashboard/investing" nuxt>Investments</v-tab>
          <v-tab to="/dashboard/calculators" nuxt>Calculators</v-tab>
        </v-tabs>
      </template>
    </v-app-bar>
  </nav>
</template>
