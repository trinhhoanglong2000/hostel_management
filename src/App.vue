<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <RouterLink to="/">Home</RouterLink>
  <RouterLink to="/about">About</RouterLink>
  <RouterView />
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@400;600;700&display=swap');
html,
body,
#app {
  height: 100%;
  width: 100%;
}
body {
  color: black;
  margin: 0;
  overflow-y: scroll;
}
* {
  font-family: 'Source Sans Pro', sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: content-box;
}
::-webkit-scrollbar{
  width: 6px;
}
::-webkit-scrollbar-track{
  background-color: #e0e0e0;
}
::-webkit-scrollbar-thumb{
  background: #888;
}
::-webkit-scrollbar-thumb:hover{
  background: #555;
}
</style>
