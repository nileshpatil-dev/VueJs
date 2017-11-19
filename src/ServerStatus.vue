<template>
  <div>
    <p>server status {{ status}}</p>
    <hr>
    <button @click="changeStatus">Change Status</button>
  </div>
</template>
<script>
export default {
  data: () => {
    return {
      status: "offline"
    };
  },
  methods: {
    changeStatus() {
        this.status = "online";
    }
  }
};
</script>
