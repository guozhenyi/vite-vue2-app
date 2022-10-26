<template>
  <div id="app">
    <div>{{ msg }}</div>
    <SubTitle></SubTitle>
  </div>
</template>

<script setup lang="jsx">
import { defineComponent } from 'vue';

const msg = 'Hello World!';

const SubTitle = defineComponent({
  name: '',
  render() {
    return <div>This is first jsx demo.</div>;
  },
});
</script>
