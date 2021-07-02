<template>
  <div>
    <div :style="{ height: height }" />
    <p>xiaobe-test-page-design-build</p>
  </div>
</template>

<script>
import { White } from "@youzan/captain-showcase";

export default {
  name: "page-design-white",

  components: {
    [White.name]: White,
  },

  props: {
    height: Number,
  },
};
</script>
