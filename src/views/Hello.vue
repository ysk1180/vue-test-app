<template>
  <div class="home">
    <HelloSomeone name="Donghee"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloSomeone from '@/components/HelloSomeone.vue';

export default defineComponent({
  name: 'Hello',
  components: {
    HelloSomeone,
  },
});
</script>
