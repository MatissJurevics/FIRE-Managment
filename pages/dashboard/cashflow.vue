<template>
  <main class="h-screen">
    <Dashbar />
    <section class="p-8 h-full bg-gray-100">
      <h1 class="text-4xl text-gray-600 font-semibold mb-8">Cash-Flow</h1>
      <div class="w-full h-3/4 grid grid-cols-5 grid-rows-2">
        <div
          class="col-span-4 row-span-2 bg-white rounded-l-2xl overflow-hidden relative"
        >
          <CashflowTable />
        </div>
        <div
          class="col-span-1 relative row-span-2 bg-white border-l border-gray-400 rounded-r-2xl overflow-hidden"
        >
          <h2 class="text-2xl font-semibold m-3">Title</h2>
          <div class="mb-3 h-1 w-96 bg-gray-300"></div>
          <p class="m-3 text-gray-600">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Exercitationem dolore est quisquam, magni placeat delectus vel nam
            unde saepe voluptatem!
          </p>

          <h3 class="ml-3 text-lg font-semibold">Tags</h3>
          <ul class="flex flex-row flex-wrap ml-3 text-white">
            <li class="bg-red-300 p-1 rounded-lg mr-3 mb-2">tag1</li>
            <li class="bg-red-300 p-1 rounded-lg mr-3 mb-2">tag2</li>
            <li class="bg-red-300 p-1 rounded-lg mr-3 mb-2">tag3</li>
            <li class="bg-red-300 p-1 rounded-lg mr-3 mb-2">tag3</li>
            <li class="bg-red-300 p-1 rounded-lg mr-3 mb-2">tag3</li>
            <li class="bg-red-300 p-1 rounded-lg mr-3 mb-2">tag3</li>
            <li class="bg-red-300 p-1 rounded-lg mr-3 mb-2">tag3</li>
            <li class="bg-red-300 p-1 rounded-lg mr-3 mb-2">tag3</li>
          </ul>

          <h3 class="text-2xl ml-3">
            Price: <span class="font-semibold">£9.99</span>
          </h3>

          <div class="mx-3 w-full mt-auto absolute bottom-3">
            <div class="w-full flex flex-row justify-around">
              <v-btn>Click</v-btn>
              <v-btn>Click</v-btn>
            </div>
          </div>
        </div>
      </div>

      <div class="w-full mt-8 pb-8 h-3/4 grid grid-cols-5 grid-rows-2 gap-4">
        <div
          class="col-span-2 row-span-2 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl"
        >
          Calendar Heatmap
        </div>
        <div
          class="col-span-1 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl"
        >
          Savings - Expenditure - Neither Pie chart
        </div>
        <div
          class="col-span-2 row-span-1 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl"
        >
          2
        </div>
        <div
          class="col-span-2 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl"
        >
          3
        </div>
        <div
          class="col-span-1 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl"
        >
          Expenditure Allocation
        </div>
      </div>
    </section>
  </main>
</template>
