<template>
  <div class="Content">
    <div class="container">
      <h1 class="Content__Title">
        {{ $t('home.title') }}
      </h1>
      <p>{{ $t('home.introduction') }}</p>
      <hello />
    </div>
  </div>
</template>

<script>
import Hello from '~/pages/_post/hello';

export default {
  components: {
    Hello
  },
  head() {
    return { title: this.$t('home.title') };
  }
};
</script>
