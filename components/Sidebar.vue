<template>
  <div class="w-auto p-8 text-white bg-blue h-screen">
    <div class="text-3xl font-black mb-8 uppercase">getartizan</div>
    <div class="mt-32">
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
</template>
<style scoped>

</style>