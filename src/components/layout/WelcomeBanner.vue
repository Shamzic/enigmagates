<template>
  <div class="container">
    {{ msg }}
  </div>
</template>

<script>
export default {
  props: {
    msg: null,
  },
  methods: {
  },
};
</script>

<style scoped>

.container {
  text-align: center;
}

</style>
