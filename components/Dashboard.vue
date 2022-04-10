<template>
  <div class="p-8 w-full bg-gray-50">
    <div class="flex justify-between">
      <div class="p-4 py-8 bg-yellow-500 w-80 rounded-3xl flex justify-evenly">
        <div class="rounded-full text-6xl py-1 text-yellow-500 bg-white">
          <span class="mdi mx-3 mdi-account-clock"></span>
        </div>
        <div>
          <div class="text-6xl text-white font-black">200</div>
          <div class="text-white font-bold text-base">Pending</div>
        </div>
      </div>

      <div class="p-4 py-8 bg-green-500 w-80 rounded-3xl flex justify-evenly">
        <div class="rounded-full text-6xl py-1 text-green-500 bg-white">
          <span class="mdi mx-3 mdi-account-clock"></span>
        </div>
        <div>
          <div class="text-6xl text-white font-black">200</div>
          <div class="text-white font-bold text-base">Approved</div>
        </div>
      </div>

      <div class="p-4 py-8 bg-indigo-500 w-80 rounded-3xl flex justify-evenly">
        <div class="rounded-full text-6xl py-1 text-indigo-500 bg-white">
          <span class="mdi mx-3 mdi-account-clock"></span>
        </div>
        <div>
          <div class="text-6xl text-white font-black">200</div>
          <div class="text-white font-bold text-base">Completed</div>
        </div>
      </div>
    </div>
    <div class="flex">
      <div class="w-4/6 mt-6">
        <div class="text-xl p-2 font-semibold">Booking History</div>
        <table class="table-fixed text-left">
          <thead>
            <tr>
              <th>S/N</th>
              <th>Title</th>
              <th>Budjet</th>
              <th>Status</th>
              <th class="w-32">Date created</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1</td>
              <td>The Sliding Mr. Bones (Next Stop, Pottersville)</td>
              <td>Malcolm Lockyer</td>
              <td>1961</td>
              <td>1961</td>
            </tr>
            <tr>
              <td>2</td>
              <td>Witchy Woman</td>
              <td>The Eagles</td>
              <td>1972</td>
              <td>1961</td>
            </tr>
            <tr>
              <td>3</td>
              <td>Shining Star</td>
              <td>Earth, Wind, and Fire</td>
              <td>1975</td>
              <td>1961</td>
            </tr>
            <tr>
              <td>4</td>
              <td>Shining Star</td>
              <td>Earth, Wind, and Fire</td>
              <td>1975</td>
              <td>1961</td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="w-2/6">
      
      </div>
    </div>
  </div>
</template>
<style scoped>
th,
td {
  padding: 10px;
}
</style>