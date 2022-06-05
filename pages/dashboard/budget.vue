<template>
    <main class="h-screen overflow-y-hidden">
    <Dashbar />
        <section class="p-8 h-full">
        <h1 class="text-4xl text-gray-600 font-semibold mb-8 ">Your Budgets</h1>
        <div class="w-full h-3/4 grid grid-cols-5 grid-rows-2">
            <div class="col-span-1 row-span-2 bg-gray-300 rounded-l-2xl flex justify-center items-center text-3xl">Goals</div>
            <div class="col-span-4 row-span-2 bg-gray-200 rounded-r-2xl flex justify-center items-center text-3xl">Details</div>
        </div>
    </section>
    </main>
</template>