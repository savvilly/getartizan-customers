<template>
  <div class="flex">
      <Sidebar />
      <Bookings />
  </div>
</template>

<script>
import Sidebar from '~/components/Sidebar.vue';
export default {
  components: { Sidebar },
  name: "IndexPage",
};
</script>
<style>
input:focus {
  outline: none !important;
}

</style>