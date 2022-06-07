<script>
export default {
  data() {
    return {
      name: "Matiss",
    };
  },
};
</script>

<template>
  <main class="h-screen overflow-y-hidden">
    <Dashbar />
    <section class="p-8 h-full">
      <h1 class="text-4xl text-gray-600 font-semibold mb-8">
        Hey {{ name }} 👋
      </h1>
      <div class="w-full h-3/4 grid grid-cols-5 grid-rows-2 gap-4">
        <div
          class="col-span-3 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl"
        >
          1
        </div>
        <div
          class="col-span-1 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl"
        >
          2
        </div>
        <div
          class="col-span-1 row-span-2 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl"
        >
          5
        </div>
        <div
          class="col-span-2 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl"
        >
          3
        </div>
        <div
          class="col-span-2 bg-gray-200 rounded-2xl flex justify-center items-center text-3xl"
        >
          4
        </div>
      </div>
    </section>
  </main>
</template>
