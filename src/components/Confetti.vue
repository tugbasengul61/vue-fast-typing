<template><div></div></template>
<script>
import confetti from "vue-confetti/src/confetti.js";
export default {
  data: () => ({
    confetti: new confetti(),
  }),
  mounted: function () {
    this.confetti.start({
      colors: ["#ff6f61", "#004c83", "#55c6a9", "#ffc82b"],
    });
  setTimeout(() => {this.confetti.stop()}, 5000);
  },
  methods: {},
};
</script>