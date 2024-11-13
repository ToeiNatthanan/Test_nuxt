<template>
  <div>
    <DashboardComponent />
  </div>
</template>

<script>
// นำเข้าคอมโพเนนต์ dashboard.vue ที่สร้างไว้
import DashboardComponent from "~/components/dashboard.vue";

export default {
  name: "IndexPage",
  components: {
    DashboardComponent,
  },
};
</script>
