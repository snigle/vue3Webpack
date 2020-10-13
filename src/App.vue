<template>
  <h2>This is a Vue 3 component!</h2>
  <button @click="increase">Clicked {{ count }} times.</button>
</template>
<script lang="ts">
import {defineComponent, ref} from "vue";
import {Vue} from "vue-class-component";
export default class extends Vue{
    count = 0
   increase () {
      this.count++
    }
};
</script>