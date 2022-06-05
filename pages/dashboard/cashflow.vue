<template>
    <main class="h-screen">
    <Dashbar />
        <section class="p-8 h-full bg-gray-100">
        <h1 class="text-4xl text-gray-600 font-semibold mb-8 ">Cash-Flow</h1>
        <div class="w-full h-3/4 grid grid-cols-5 grid-rows-2">
            <div class="col-span-4 row-span-2 bg-white rounded-l-2xl overflow-hidden relative">
                <CashflowTable />
            </div>
            <div class="col-span-1 row-span-2 bg-gray-200 rounded-r-2xl flex justify-center items-center text-3xl">Details</div>
         </div>

         <div class="w-full mt-8 pb-8 h-3/4 grid grid-cols-5 grid-rows-2 gap-4">
            <div class="col-span-2 row-span-2 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl">Calendar Heatmap</div>
            <div class="col-span-1 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl">Savings - Expenditure - Neither Pie chart</div>
            <div class="col-span-2 row-span-1 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl">2</div>
            <div class="col-span-2 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl">3</div>
            <div class="col-span-1 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl">Expenditure Allocation</div>
         </div>


    </section>
    </main>
</template>

