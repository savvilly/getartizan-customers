<template>
  <div id="sidebar" class="w-80 p-8 text-black h-screen border border-l-gray">
    <div>
      <img src="@/static/logo.png" class="w-52" alt="" />
    </div>
    <div class="mt-32">
      <NuxtLink to="/">
        <div class="text-lg capitalize my-8">
          <span class="mdi mx-3 mdi-view-dashboard"></span>dashboard
        </div>
      </NuxtLink>
      <NuxtLink to="/bookings">
        <div class="text-lg capitalize my-8 opacity-40">
          <span class="mdi mx-3 mdi-book"></span>
          bookings
        </div>
      </NuxtLink>
      <NuxtLink to="/account">
        <div class="text-lg capitalize my-8 opacity-40">
          <span class="mdi mx-3 mdi-account-circle"></span>
          account
        </div>
      </NuxtLink>
    </div>
  </div>
</template>
<style scoped>
@media (max-width: 600px) {
  #sidebar {
    display: none;
  }
}
</style>