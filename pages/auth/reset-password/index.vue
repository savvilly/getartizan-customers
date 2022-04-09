<template>
  <div class="lg:flex">
    <div class="lg:w-6/12 lg:block hidden h-screen">
      <img src="@/static/reset-password.jpg" class="h-screen" alt="">
    </div>
    <div class="lg:w-6/12 grid place-items-center h-screen">
      <div class="w-full lg:px-20 p-8">
        <div class="text-3xl font-bold text-blue">Reset password</div>
        <div>
          <input
            type="password"
            placeholder="New Password"
            class="
              border
              my-3
              border-t-0
              text-sm
              w-full
              border-l-0 border-r-0
              p-2
            "
          />
        </div>
        <div>
          <input
            type="password"
            placeholder="Confirm New Password"
            class="
              border
              my-3
              border-t-0
              text-sm
              w-full
              border-l-0 border-r-0
              p-2
            "
          />
        </div>
        <div class="text-center my-6">
          <NuxtLink to="/auth/login">
            <input
              type="button"
              value="Reset"
              class="uppercase text-sm p-3 bg-blue text-white w-full"
            />
          </NuxtLink>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins&display=swap");
input:focus {
  outline: none !important;
}
div {
  font-family: "Poppins", sans-serif;
}
</style>