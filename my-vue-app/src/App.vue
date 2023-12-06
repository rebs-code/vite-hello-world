<script>
import TitleComponent from './components/TitleComponent.vue';
import JumboComponent from './components/JumboComponent.vue';

export default {
  name: "App",
  components: {
    TitleComponent,
    JumboComponent,
  }
}
</script>

<template>
  <div>
    <TitleComponent />
    <JumboComponent />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
