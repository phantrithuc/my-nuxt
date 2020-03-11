<template>
  <div v-html="hello"></div>
</template>

<script>
import hello from '~/markdown/hello.md';

export default {
  computed: {
    hello() {
      return hello;
    }
  }
};
</script>
