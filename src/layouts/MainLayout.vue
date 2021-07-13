<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar style="background-color: #404550; height: 48px !important;">

        <q-toolbar-title style="color: #212325;">
          SCJB Benchmark
        </q-toolbar-title>

      </q-toolbar>
      <q-toolbar class="control-panel">

        <q-toolbar-title style="color: #FFFFFF; font-size: 14px;">
          Case Types
        </q-toolbar-title>

      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'MainLayout',

  setup () {
  }
})
</script>
<style>
  .control-panel {
    box-sizing: border-box;
    height: 48px !important;
    border: 1px solid #000000;
    border-radius: 2px;
    background-color: #5E5E5E;
    box-shadow: 0 0 4px 0 rgba(0,0,0,0.5), 0 0 8px 0 rgba(0,0,0,0.08);
  }
</style>
