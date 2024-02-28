<script setup lang="ts">
const items = [
    {
  slot: 'mikrotik',
  label: 'สินค้าลดราคา'
}
]

</script>

<template>

  <UTabs :items="items" class="w-full    ">
    <template #mikrotik="{ item }">
    <UCard >
    <template #mikrotik="{ item }">

      <p class="mt-1 text-sm text-gray-500 dark:text-gray-400">
        MikroTik features include robustness, affordability, scalability,
        versatility, and extensive networking capabilities.
      </p>
    </template>
        <div class="text-white  lg:mt-5 xl:mt-0 sm:mt-0 mt-5 ">
          <div class="grid grid-cols-3 ">
            <div class="mb-3">
              <div class='relative border-2 rounded-md h-[12dvw] mx-2 transition-transform hover:scale-105 cursor-pointer'>
                <UBadge class="absolute sm:top-[-1dvw] top-[-3dvw] sm:text-lg text-[10px] sm:right-[-1dvw] right-[-3dvw] bg-red-700" variant="">SALE</UBadge>
                <img src="/pcisco.jpeg" class=" h-full rounded-md ">
              </div>
              <div class='flex flex-cols items-center sm:justify-center  mt-2  mx-2 space-x-2 '>
                <div>
                  <h1 class="text-red-500 xl:text-2xl ">9,999 ฿</h1>
                  <span class="text-gray-400 line-through text-[14px] sm:hidden flex">10,000 ฿</span>
                </div>
                <div>
                  <span class="text-gray-400 line-through text-[14px] xl:flex hidden">10,000 ฿</span>
                </div>
              </div>
            </div>

            <div class="mb-3">
              <div class='relative border-2 rounded-md h-[12dvw] mx-2 transition-transform hover:scale-105 cursor-pointer'>
                <UBadge class="absolute sm:top-[-1dvw] top-[-3dvw] sm:text-lg text-[10px] sm:right-[-1dvw] right-[-3dvw] bg-red-700" variant="">SALE</UBadge>
                <img src="/pcisco.jpeg" class=" h-full rounded-md ">
              </div>
              <div class='flex flex-cols items-center sm:justify-center  mt-2  mx-2 space-x-2 '>
                <div>
                  <h1 class="text-red-500 xl:text-2xl ">9,999 ฿</h1>
                  <span class="text-gray-400 line-through text-[14px] sm:hidden flex">10,000 ฿</span>
                </div>
                <div>
                  <span class="text-gray-400 line-through text-[14px] xl:flex hidden">10,000 ฿</span>
                </div>
              </div>
            </div>

            <div class="mb-3">
              <div class='relative border-2 rounded-md h-[12dvw] mx-2 transition-transform hover:scale-105 cursor-pointer'>
                <UBadge class="absolute sm:top-[-1dvw] top-[-3dvw] sm:text-lg text-[10px] sm:right-[-1dvw] right-[-3dvw] bg-red-700" variant="">SALE</UBadge>
                <img src="/pcisco.jpeg" class=" h-full rounded-md ">
              </div>
              <div class='flex flex-cols items-center sm:justify-center  mt-2  mx-2 space-x-2 '>
                <div>
                  <h1 class="text-red-500 xl:text-2xl ">9,999 ฿</h1>
                  <span class="text-gray-400 line-through text-[14px] sm:hidden flex">10,000 ฿</span>
                </div>
                <div>
                  <span class="text-gray-400 line-through text-[14px] xl:flex hidden">10,000 ฿</span>
                </div>
              </div>
            </div>

          </div>
          <div class='flex items-center justify-center  rounded-md mx-2
            space-x-2 transition-transform hover:scale-105 w-full'>
            <button  class="w-full bg-red-700 rounded-md h-10 lg:mt-7 xl:mt-0 sm:mt-0 mt-5">ดูสินค้าลดราคาเพิ่มเติม</button>
          </div>
        </div>

    </UCard>
    </template>
  </UTabs>
</template>

