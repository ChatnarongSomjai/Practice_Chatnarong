<template>
  <dir>
    <input v-model="text" />
    <h1>{{ text }}</h1>
  </dir>
</template>
<script>
export default {
  data() {
    return {
      text: "Test",
    };
  },
};
</script>