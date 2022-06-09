<template>
  <div class="pt-8 text-center">
    <div class="text-3xl">Update Information</div>
    <div class="w-full mx-auto">
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
            bg-gray-50
          "
        />
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
            bg-gray-50
          "
        />
      </div>
      <div>
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
            bg-gray-50
          "
        />
      </div>
      <div>
        <select
          class="
            border
            my-3
            border-t-0
            text-sm
            w-full
            border-l-0 border-r-0
            p-2
            bg-gray-50
          "
        >
          <option value="">Select your gender</option>
        </select>
      </div>
      <div>
        <select
          class="
            border
            my-3
            border-t-0
            text-sm
            w-full
            border-l-0 border-r-0
            p-2
            bg-gray-50
          "
        >
          <option value="">Select your state</option>
        </select>
      </div>
      <div>
        <select
          class="
            border
            my-3
            border-t-0
            text-sm
            w-full
            border-l-0 border-r-0
            p-2
            bg-gray-50
          "
        >
          <option value="">Select your LGA</option>
        </select>
      </div>
      <div>
        <select
          class="
            border
            my-3
            border-t-0
            text-sm
            w-full
            border-l-0 border-r-0
            p-2
            bg-gray-50
          "
        >
          <option value="">Select your Area of Specialization</option>
        </select>
      </div>
    </div>
    <div class="text-center my-6">
      <button class="bg-blue text-white p-4 w-44 font-bold uppercase">
        Update
      </button>
    </div>
  </div>
</template>
<style scoped>
input,
div,
textarea,
select {
  width: 90% !important;
}
textarea:focus {
  outline: none;
}
/* input::placeholder, textarea::placeholder{
    color: #000;
} */
@media (max-width: 600px) {
  input,
  div,
  textarea,
  select {
    width: 100% !important;
  }
}
</style>