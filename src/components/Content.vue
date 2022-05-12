<template>
  <div class="main">
    <p>{{ text }}</p>
    <mdiHandBackRightOutline size="48" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import mdiHandBackRightOutline from "vue-material-design-icons/HandBackRightOutline.vue";

export default defineComponent({
  name: "Content",
  props: {},
  components: {
    mdiHandBackRightOutline,
  },
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
