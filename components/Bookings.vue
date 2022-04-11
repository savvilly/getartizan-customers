<template>
  <div class="text-center p-8">
    <div class="text-3xl font-bold my-4">Create Booking</div>
    <div class="lg:mx-20">
      <div>
        <input
          class="border my-3 border-t-0 text-sm border-l-0 border-r-0 p-2"
          type="text"
          placeholder="Title"
        />
      </div>
      <div>
        <select
          class="
            border
            my-3
            border-t-0
            bg-transparent
            text-sm
            border-l-0 border-r-0
            p-2
          "
        >
          <option value="">Choose Category</option>
        </select>
      </div>
      <div>
        <input
          class="border my-3 border-t-0 text-sm border-l-0 border-r-0 p-2"
          type="text"
          placeholder="Artisan Location"
        />
      </div>
      <div>
        <input
          class="border my-3 border-t-0 text-sm border-l-0 border-r-0 p-2"
          type="text"
          placeholder="Budget"
        />
      </div>
      <div>
        <input
          class="border my-3 border-t-0 text-sm border-l-0 border-r-0 p-2"
          type="text"
          placeholder="Job Address"
        />
      </div>
      <div>
        <textarea
          class="border my-3 border-t-0 text-sm border-l-0 border-r-0 p-2"
          placeholder="Job Description"
        ></textarea>
      </div>
      <div>
        <button class="uppercase my-4 bg-blue p-4 w-44 text-white font-bold">
          create task
        </button>
      </div>
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