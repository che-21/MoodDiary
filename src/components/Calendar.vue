<template>
  <vue-cal
    style="height: 500px"
    :time="false"
    active-view="month"
  />
</template>

<script>
import VueCal from "vue-cal";
import "vue-cal/dist/vuecal.css";

export default {
  components: {
    VueCal,
  },
};
</script>