<template>
  <VueDatePicker :value="date"></VueDatePicker>
</template>

<script>
import { VueDatePicker } from "@mathieustan/vue-datepicker";
export default {
  name: "app",
  components: {
    VueDatePicker
  },
  data: () => ({
    date: new Date()
  })
};
</script>
