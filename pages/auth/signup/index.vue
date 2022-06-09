<template>
  <div class="lg:flex bg-gray">
    <div class="lg:w-2/3 relative">
      <img class="w-full h-full" src="@/static/auth/Image1.jpg" alt="" />
      <div class="w-full h-full opacity-50 bg-black absolute top-0">
        <div class="text-white absolute bottom-20 sm:bottom-40 lg:px-20 px-8">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat,
          neque. Ducimus dolor cupiditate delectus? Ducimus veniam, beatae
          libero, consectetur iste omnis repellat et obcaecati doloremque porro,
          itaque assumenda aperiam labore!
        </div>
      </div>
    </div>
    <div class="lg:w-2/3 lg:h-screen">
      <div class="mt-10 lg:block hidden">
        <img class="w-80 mx-auto" src="@/static/logo.png" alt="" />
      </div>
      <div
        class="
          sm:absolute
          top-80
          lg:w-4/5 lg:mt-0
          mx-auto
          lg:my-0
          w-full
          p-8
          shadow-lg
          rounded-md
          bg-white
        "
      >
        <div class="text-3xl mb-6 text-blue font-bold">Sign Up</div>
        <div>
          <input
            type="text"
            placeholder="Full Name"
            class="border-none bg-gray my-3 text-sm w-full p-2 bg-gray-50"
          />
        </div>
        <div class="lg:flex justify-between">
          <div class="lg:w-56">
            <input
              type="email"
              placeholder="Email"
              class="border-none bg-gray my-3 text-sm w-full p-2 bg-gray-50"
            />
          </div>
          <div class="lg:w-56">
            <input
              type="number"
              placeholder="Phone Number"
              class="border-none bg-gray my-3 text-sm w-full p-2 bg-gray-50"
            />
          </div>
        </div>
        <div class="lg:flex justify-between">
          <div class="lg:w-56">
            <select
              class="border-none bg-gray my-3 text-sm w-full p-2 bg-gray-50"
            >
              <option value="">Select your gender</option>
            </select>
          </div>
          <div class="lg:w-56">
            <select
              class="border-none bg-gray my-3 text-sm w-full p-2 bg-gray-50"
            >
              <option value="">Select your state</option>
            </select>
          </div>
        </div>
        <div class="lg:flex justify-between">
          <div class="lg:w-56">
            <select
              class="border-none bg-gray my-3 text-sm w-full p-2 bg-gray-50"
            >
              <option value="">Select your LGA</option>
            </select>
          </div>
          <div class="lg:w-56">
            <select
              class="border-none bg-gray my-3 text-sm w-full p-2 bg-gray-50"
            >
              <option value="">Select your Area of Specialization</option>
            </select>
          </div>
        </div>
        <div class="lg:flex justify-between">
          <div class="lg:w-56">
            <input
              type="password"
              placeholder="Password"
              class="border-none bg-gray my-3 text-sm w-full p-2 bg-gray-50"
            />
          </div>
          <div class="lg:w-56">
            <input
              type="password"
              placeholder="Confirm Password"
              class="border-none bg-gray my-3 text-sm w-full p-2 bg-gray-50"
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