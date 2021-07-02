<template>
  <div>
    <div :style="{ height: height }" />
  </div>
</template>

<script>
export default {
  name: "white-case",

  components: {
    [White.name]: White,
  },

  props: {
    height: Number,
  },
};
</script>
