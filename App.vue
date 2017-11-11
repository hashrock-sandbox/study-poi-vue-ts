<template>
  <div id="main">
    <h1>Hello World!</h1>
    <input v-model="text">
    <p>input: {{text}}</p>
  </div>
</template>
<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  data(){
    return {
      text: "Hello There"
    }
  },
  mounted() {
    console.log(this.text)
  }
})
</script>

