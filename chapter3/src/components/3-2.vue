<template>
  <div>
    {{ count }}
  </div>
</template>
<script>
  import store from 'src/stores';
  export default {
    computed: {
      count () {
        return store.state.count;
      }
    }
  }
</script>
