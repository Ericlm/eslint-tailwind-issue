<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'

const is = true
</script>

<template>
  <header>
    <img alt="Vue logo" class="size-16 bg-red-600" src="./assets/logo.svg" :class="[{'text-yala': is}]" />

    <div class="text-yolo" :class="[is ? 'text-yulu' : 'text-red-50']">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main :class="{'text-yepee': is}">
    <TheWelcome />
  </main>
</template>
