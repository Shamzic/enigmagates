<template>
  <div class="container mt-2">
    <p class="mt-2">ChatBox</p>
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
  border:  2px solid rgba(170, 170, 170, .6);
  height: 500px;
}

</style>
