<template>
  <v-app>
    <v-main>
      <CustomTextField>
        <template #prepend>
          <v-icon>mdi-email</v-icon>
        </template>
      </CustomTextField>
    </v-main>
  </v-app>
</template>

<script setup lang="ts">
import CustomTextField from "./components/CustomTextField.vue";
</script>
