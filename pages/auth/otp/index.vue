<template>
  <div class="lg:flex">
    <div class="lg:w-1/3 bg-blue lg:block hidden h-screen">
      <img src="@/static/otp.png" class="mt-32" alt="">
    </div>
    <div class="lg:w-2/3 grid place-items-center h-screen">
      <div class="w-full lg:px-20 p-8">
        <div class="text-3xl mb-6 text-blue font-bold">Confirm Phone Number</div>
        <div>
          <input
            type="number"
            placeholder="Enter the 6 digits pin sent to your phone number"
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
          <NuxtLink to="/">
            <input
              type="button"
              value="Sign Up"
              class="uppercase text-sm p-3 bg-blue text-white lg:w-96 w-full"
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