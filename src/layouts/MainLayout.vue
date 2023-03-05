<template>
  <q-layout>
    <q-header bordered class="bg-white text-primary">
        <q-toolbar>
          <q-toolbar-title class="text-center">
            <q-avatar>
              <img src="https://cdn.quasar.dev/logo-v2/svg/logo.svg">
            </q-avatar>
            Boston
          </q-toolbar-title>
        </q-toolbar>
      </q-header>
    <q-footer bordered class="bg-white text-primary">
      <q-tabs
        v-model="tab"
        indicator-color="transparent"
        active-color="white"
        class="text-grey-5 shadow-2"
      >
        <q-tab name="/" icon="home" label="Home" />
        <q-tab name="/workout" icon="fitness_center" label="workout" />
        <q-tab name="/history" icon="movie" label="History" />
        <q-tab name="/plan" icon="format_list_bulleted" label="Plan" />
        <q-tab name="/profile" icon="account_circle" label="Profile" />

      </q-tabs>
    </q-footer>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'MainLayout'

})
</script>
