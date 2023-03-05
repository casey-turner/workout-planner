<template>
  <q-page class="flex flex-center" >
    <q-scroll-area class="form-style">
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
      <div>
        <q-btn size="lg" label="Login" />
      </div>
    </q-scroll-area>
  </q-page>
</template>

<script setup>

</script>
