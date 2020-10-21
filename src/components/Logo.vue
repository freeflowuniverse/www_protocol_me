<template>
<img src="/logo.png" alt="Crystal Twin" style="width:34px;height:34px;">
</template>

<script>
export default {
  props: {
    width: {
      type: Number,
      default: 40
    }
  },

  computed: {
    getWidth() {
      return this.width;
    },

    getHeight() {
      return Math.ceil((this.getWidth / 48) * 48);
    }
  }
};
</script>

