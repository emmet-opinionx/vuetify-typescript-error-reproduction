<template>
  <v-text-field>
    <template #prepend>
      <div class="text-red">
        <slot name="prepend"></slot>
      </div>
    </template>
  </v-text-field>
</template>

<script setup lang="ts"></script>
