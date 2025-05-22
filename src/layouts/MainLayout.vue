<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar>
        <q-toolbar-title> Quasar App </q-toolbar-title>

        <div>Quasar v{{ $q.version }}</div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer class="bg-grey-10 text-white q-pa-md">
      <div class="row justify-between items-center">
        <div>&copy; 2025 SuaMarca. Todos os direitos reservados.</div>
        <div class="row q-gutter-sm">
          <q-btn dense flat icon="mdi-instagram" />
          <q-btn dense flat icon="mdi-whatsapp" />
        </div>
      </div>
    </q-footer>
  </q-layout>
</template>

<script setup lang="ts"></script>
