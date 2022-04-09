<template>
  <div class="lg:flex">
    <div class="lg:w-6/12 lg:block hidden h-screen">
      <img src="@/static/forgot-password.jpg" class="h-screen" alt="" />
    </div>
    <div class="lg:w-6/12 grid place-items-center h-screen">
      <div class="w-full lg:px-20 p-8">
        <div class="text-3xl font-bold text-blue">Forgot password</div>
        <div class="text-sm">
          Enter your mail so we'll send you a link to reset your password
        </div>
        <div>
          <input
            type="email"
            placeholder="Email"
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
          <NuxtLink to="/auth/reset-password">
            <input
              type="button"
              value="Submit"
              class="uppercase text-sm p-3 bg-blue text-white w-full"
            />
          </NuxtLink>
        </div>
        <div class="capitalize text-sm">
          chai i remember my password now
          <NuxtLink class="text-blue" to="/auth/login">Login</NuxtLink>
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