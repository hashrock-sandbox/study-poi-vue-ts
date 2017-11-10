<template>
  <div id="main">
    <h1>Hello World!</h1>
    <input v-model="text">
    <p>input: {{text}}</p>
  </div>
</template>
<script lang="ts">
import Vue from "vue";
import Component from "vue-class-component";

@Component({})
export default class App extends Vue {
  text: string = "Hello There";
  mounted() {}
}
</script>

