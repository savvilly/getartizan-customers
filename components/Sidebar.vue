<template>
  <div class="">
    <div
      v-if="sidebar"
      class="lg:p-8 p-3 w-72 text-black h-screen border border-l-gray"
    >
      <div>
        <img src="@/static/logo.png" class="w-52" alt="" />
      </div>
      <div class="mt-20 ml-6">
        <NuxtLink to="/">
          <div class="text-lg capitalize my-8">
            <span class="mdi mx-3 mdi-view-dashboard"></span>dashboard
          </div>
        </NuxtLink>
        <NuxtLink to="/bookings">
          <div class="text-lg capitalize my-8">
            <span class="mdi mx-3 mdi-book"></span>
            bookings
          </div>
        </NuxtLink>
        <NuxtLink to="/account">
          <div class="text-lg capitalize my-8">
            <span class="mdi mx-3 mdi-account-circle"></span>
            account
          </div>
        </NuxtLink>
      </div>
    </div>
    <div class="lg:hidden block absolute w-full left-0 top-0 h-20">
      <div @click="toggle" class="p-3">
        <button>
          <img src="@/static/hamburger.png" class="w-10" alt="" />
        </button>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      sidebar: true,
    };
  },
  mounted() {
    const width = window.innerWidth;
    if (width <= 800) {
      this.toggle();
    }
  },
  methods: {
    toggle() {
      this.sidebar = !this.sidebar;
    },
  },
};
</script>
<style scoped>
@media (max-width: 600px) {
  #sidebar {
    display: none;
  }
}
a.nuxt-link-exact-active {
  color: #6545e4;
}
</style>