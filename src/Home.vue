<template>
  <div>
      <app-server-status v-for='i in 5' :data="i"
           :key="i" > </app-server-status>
      dasd
  </div>
</template>
<script>
import ServerStatus from "./ServerStatus.vue";
export default {
  components: {
    "app-server-status": ServerStatus
  }
};
</script>
