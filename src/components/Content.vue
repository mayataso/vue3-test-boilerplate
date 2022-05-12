<template>
  <div class="main">
    <p>{{ text }}</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Content",
  props: {},
  setup() {
    const text = "Hi, there.";

    return { text };
  },
});
</script>

<style scoped lang="scss">
p {
  font-size: 32px;
}
</style>
