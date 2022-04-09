<template>
  <div class="lg:flex">
    <div class="lg:w-1/3 bg-blue lg:block hidden h-screen">
      <img src="@/static/onboarding.png" class="mt-20" alt="">
    </div>
    <div class="lg:w-2/3 grid place-items-center h-screen">
      <div class="w-full lg:px-20 p-8">
        <div class="text-3xl mb-6 text-blue font-bold">Onboarding</div>
        <input class="hidden" type="file" id="photo" name="photo" />
        <div
          class="
            w-32
            mb-6
            mx-auto
            h-32
            border border-lavender
            rounded-xl
            text-center
          "
        >
          <label class="text-sm" for="photo">Upload Photo</label>
        </div>

        <div class="text-base">Guarantor Details</div>
        <div>
          <input
            type="text"
            placeholder="Enter Guarantor Name "
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
            type="number"
            placeholder="Enter Guarantor Phone Number "
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
              value="Register"
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