<template>
  <q-page>
    <h1>Register</h1>
    <q-scroll-area class="form-style">
      <q-input rounded outlined bottom-slots label="First name" counter :dense="dense">
        <template v-slot:append>
          <q-icon name="close" @click="text = ''" class="cursor-pointer" />
        </template>
      </q-input>
      <q-input rounded outlined bottom-slots label="Last name" counter :dense="dense">
        <template v-slot:append>
          <q-icon name="close" @click="text = ''" class="cursor-pointer" />
        </template>
      </q-input>
      <q-input rounded outlined bottom-slots label="Email" counter :dense="dense">
        <template v-slot:append>
          <q-icon name="close" @click="text = ''" class="cursor-pointer" />
        </template>
      </q-input>
      <q-input rounded outlined bottom-slots label="Password" counter :dense="dense">
        <template v-slot:append>
          <q-icon name="close" @click="text = ''" class="cursor-pointer" />
        </template>
      </q-input>
      <q-input rounded outlined bottom-slots label="Confirm Password" counter :dense="dense">
        <template v-slot:append>
          <q-icon name="close" @click="text = ''" class="cursor-pointer" />
        </template>
      </q-input>

      <div>
        <q-btn size="lg" label="Register" />
      </div>
    </q-scroll-area>
  </q-page>
</template>
<script setup></script>
