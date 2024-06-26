<template>
  <div class="text-h4">Home</div>
  <div>
    {{ $route.name }}
    <br />
    {{ $route.meta }}
  </div>
</template>

<script>
export default {
  setup() {
    return {};
  },
};
</script>

<style lang="scss" scoped></style>
<route lang="yaml">
name: home-page
meta:
  requiresAuth: true
</route>
