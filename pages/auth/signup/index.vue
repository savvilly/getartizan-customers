<template>
  <div class="lg:flex">
    <div class="lg:w-1/3 bg-blue lg:block hidden h-screen">
      <img class="mt-20 move" src="@/static/signup.png" alt="">
    </div>
    <div class="lg:w-2/3 grid place-items-center h-screen">
      <div class="w-full lg:px-20 p-8">
        <div class="text-3xl mb-6 text-blue font-bold">Sign Up</div>
        <div>
          <input
            type="text"
            placeholder="Full Name"
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
        <div class="lg:flex justify-between">
          <div class="lg:w-5/12">
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
          <div class="lg:w-5/12">
            <input
              type="number"
              placeholder="Phone Number"
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
        </div>
        <div class="lg:flex justify-between">
          <div class="lg:w-5/12">
            <select
              class="
                border
                my-3
                border-t-0
                text-sm
                w-full
                border-l-0 border-r-0
                p-2
                bg-transparent
              "
            >
              <option value="">Select your gender</option>
            </select>
          </div>
          <div class="lg:w-5/12">
            <select
              class="
                border
                my-3
                border-t-0
                text-sm
                w-full
                border-l-0 border-r-0
                p-2
                bg-transparent
              "
            >
              <option value="">Select your state</option>
            </select>
          </div>
        </div>
        <div class="lg:flex justify-between">
          <div class="lg:w-5/12">
            <select
              class="
                border
                my-3
                border-t-0
                text-sm
                w-full
                border-l-0 border-r-0
                p-2
                bg-transparent
              "
            >
              <option value="">Select your LGA</option>
            </select>
          </div>
          <div class="lg:w-5/12">
            <select
              class="
                border
                my-3
                border-t-0
                text-sm
                w-full
                border-l-0 border-r-0
                p-2
                bg-transparent
              "
            >
              <option value="">Select your Area of Specialization</option>
            </select>
          </div>
        </div>
        <div class="lg:flex justify-between">
          <div class="lg:w-5/12">
            <input
              type="password"
              placeholder="Password"
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
          <div class="lg:w-5/12">
            <input
              type="password"
              placeholder="Confirm Password"
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
        </div>
        <div class="text-center my-6">
          <NuxtLink to="/auth/otp">
            <input
              type="button"
              value="Next"
              class="uppercase text-sm p-3 bg-blue text-white lg:w-96 w-full"
            />
          </NuxtLink>
        </div>
        <!-- <div class="text-center capitalize text-sm">or sign up with</div>
        <div class="text-center">
            
        </div> -->
        <div class="text-center capitalize text-sm">
          already have an account?
          <NuxtLink to="/auth/login" class="text-blue mx-3">Login</NuxtLink>
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