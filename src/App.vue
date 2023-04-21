<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import { Dropdown, ListGroup, ListGroupItem } from 'flowbite-vue'
</script>

<template>
  <h1 className="text-3xl font-bold underline">
    Fancy tailwind h1 header
  </h1>
  <p>
    <a href="https://tailwindcss.com/docs/guides/vite#vue">Source: https://tailwindcss.com/docs/guides/vite#vue</a>
  </p>
  <hr>

  <h1 class="mt-6">
    Flowbite dropdown
  </h1>
  <dropdown text="Click me" placement="top">
    <list-group>
      <list-group-item>Item #1</list-group-item>
      <list-group-item>Item #2</list-group-item>
      <list-group-item>Item #3</list-group-item>
    </list-group>
  </dropdown>
  <p>
    <a href="https://flowbite-vue.com/pages/getting-started">Source: https://flowbite-vue.com/pages/getting-started</a>
  </p>
  <hr>

  <h1 class="mt-6">
    Original Vite HelloWorld component (without styles):
  </h1>
  <div>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
    <a href="https://vitejs.dev" target="_blank">
      <img src="./assets/vite.svg" class="logo vite" alt="Vite logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>
