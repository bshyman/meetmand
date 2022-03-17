<template>
  <div class="m-4">
    <header style="height: 250px">
      <div class="flex justify-center items-center" style="height: 200px">
        13 Storybook Lane
      </div>
      <div class="w-2/3 mx-auto">
        <NavigationTabs></NavigationTabs>
      </div>
    </header>

    <div class="mt-10">
      <img src="https://picsum.photos/2000/330" class="mt-4" alt="hero" />
    </div>

    <div class="grid grid-cols-6 gap-x-4 gap-y-4 mt-4">
      <div
        class="col-span-4 border-2 border-indigo-600 rounded"
        style="height: 800px"
      ></div>

      <div class="col-span-2 grid grid-rows-2 grid-cols-1 gap-y-4">
        <div class="border-2 border-indigo-600 rounded h-full"></div>
        <div class="border-2 border-indigo-600 rounded h-full"></div>
      </div>

      <div
        class="col-span-3 border-2 border-indigo-600 rounded"
        style="height: 800px"
      ></div>
      <div class="col-span-3 border-2 border-indigo-600 rounded"></div>

      <div
        class="col-span-6 border-2 border-indigo-600 rounded flex flex-col w-full"
        style="height: 600px"
      >
        <div class="w-full bg-pink-300 h-full">
          <div class="p-20 grid grid-cols-6 gap-x-4" style="height: 400px">
            <div class="border-2 border-indigo-600 rounded h-full"></div>
            <div class="border-2 border-indigo-600 rounded h-full"></div>
            <div class="border-2 border-indigo-600 rounded h-full"></div>
            <div class="border-2 border-indigo-600 rounded h-full"></div>
            <div class="border-2 border-indigo-600 rounded h-full"></div>
            <div class="border-2 border-indigo-600 rounded h-full"></div>
          </div>
        </div>
        <div class="w-full bg-pink-800 h-full"></div>
      </div>
    </div>
  </div>
</template>

<script>
import NavigationTabs from '~/components/NavigationTabs'

export default {
  name: 'IndexPage',
  components: { NavigationTabs },
}
</script>
