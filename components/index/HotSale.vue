<script setup lang="ts">
const items = [
    {
  slot: 'mikrotik',
  label: 'Mikrotik'
}, {
  slot: 'cisco',
  label: 'Cisco'
}
]

</script>

<template>
  <UTabs :items="items" class="w-full  ">
    <template #mikrotik="{ item }">
      <UCard  class="border-2  ">
        <template #header>
          <h3 class="text-base font-semibold leading-6 text-gray-900 dark:text-white">
            {{ item.label }}
          </h3>
          <p class="mt-1 text-sm text-gray-500 dark:text-gray-400">
            Features of Cisco networking solutions include stability, performance,
            security, management capabilities, and flexibility
          </p>
        </template>

        <div class="text-white w-full mt-5  sm:mx-0">
          <div class="grid grid-cols-3 ">

            <div class="mb-5 ">
              <div class='relative object-cover rounded-md  mx-2 transition-transform hover:scale-105'>
                <UBadge class="absolute top-[-1dvw]  sm:right-[-1dvw] right-[-3dvw]
                 h-4 sm:h-8 sm:text-lg text-[10px] bg-red-700" variant="">SALE</UBadge>
                <div class="flex h-[12dvw] ">
                  <div class="h-full w-full ">
                    <img src="/pmikrotik.jpeg" class="rounded-md  h-full w-screen" >
                  </div>
                </div>
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

            <div class="mb-5 ">
              <div class='relative object-cover rounded-md  mx-2 transition-transform hover:scale-105'>
                <UBadge class="absolute top-[-1dvw]  sm:right-[-1dvw] right-[-3dvw]
                 h-4 sm:h-8 sm:text-lg text-[10px] bg-red-700" variant="">SALE</UBadge>
                <div class="flex h-[12dvw] ">
                  <div class="h-full w-full ">
                    <img src="/pmikrotik.jpeg" class="rounded-md  h-full w-screen" >
                  </div>
                </div>
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

            <div class="mb-5 ">
              <div class='relative object-cover rounded-md  mx-2 transition-transform hover:scale-105'>
                <UBadge class="absolute top-[-1dvw]  sm:right-[-1dvw] right-[-3dvw]
                 h-4 sm:h-8 sm:text-lg text-[10px] bg-red-700" variant="">SALE</UBadge>
                <div class="flex h-[12dvw] ">
                  <div class="h-full w-full ">
                    <img src="/pmikrotik.jpeg" class="rounded-md  h-full w-screen" >
                  </div>
                </div>
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

            <div class="mb-5 ">
              <div class='relative object-cover rounded-md  mx-2 transition-transform hover:scale-105'>
                <UBadge class="absolute top-[-1dvw]  sm:right-[-1dvw] right-[-3dvw]
                 h-4 sm:h-8 sm:text-lg text-[10px] bg-red-700" variant="">SALE</UBadge>
                <div class="flex h-[12dvw] ">
                  <div class="h-full w-full ">
                    <img src="/pmikrotik.jpeg" class="rounded-md  h-full w-screen" >
                  </div>
                </div>
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

            <div class="mb-5 ">
              <div class='relative object-cover rounded-md  mx-2 transition-transform hover:scale-105'>
                <UBadge class="absolute top-[-1dvw]  sm:right-[-1dvw] right-[-3dvw]
                 h-4 sm:h-8 sm:text-lg text-[10px] bg-red-700" variant="">SALE</UBadge>
                <div class="flex h-[12dvw] ">
                  <div class="h-full w-full ">
                    <img src="/pmikrotik.jpeg" class="rounded-md  h-full w-screen" >
                  </div>
                </div>
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

            <div class="mb-5 ">
              <div class='relative object-cover rounded-md  mx-2 transition-transform hover:scale-105'>
                <UBadge class="absolute top-[-1dvw]  sm:right-[-1dvw] right-[-3dvw]
                 h-4 sm:h-8 sm:text-lg text-[10px] bg-red-700" variant="">SALE</UBadge>
                <div class="flex h-[12dvw] ">
                  <div class="h-full w-full ">
                    <img src="/pmikrotik.jpeg" class="rounded-md  h-full w-screen" >
                  </div>
                </div>
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
        </div>
      </UCard> <div class="h-[6dvw] py-1 w-full ">

      <div class="h-full w-full cursor-pointer ">
        <img src="/shoppee.png" class="rounded-md  sm:h-full w-full" >
      </div>
    </div>
    </template>

    <template #cisco="{ item }">
      <UCard  class="border-2 ">
        <template #header>
          <h3 class="text-base font-semibold leading-6 text-gray-900 dark:text-white">
            {{ item.label }}
          </h3>
          <p class="mt-1 text-sm text-gray-500 dark:text-gray-400">
            Features of Cisco networking solutions include stability, performance,
            security, management capabilities, and flexibility
          </p>
        </template>

        <div class="text-white w-full mt-5 ">
          <div class="grid grid-cols-3 ">

            <div class="mb-5 ">
              <div class='relative object-cover rounded-md  mx-2 transition-transform hover:scale-105'>
                <UBadge class="absolute top-[-1dvw] right-[-1dvw]
                 h-4 sm:h-8 sm:text-lg text-[10px] bg-red-700" variant="">SALE</UBadge>
                <div class="flex h-[12dvw] ">
                  <div class="h-full w-full ">
                    <img src="/pcisco.jpeg" class="rounded-md  h-full w-screen" >
                  </div>
                </div>
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

            <div class="mb-5 ">
              <div class='relative object-cover rounded-md  mx-2 transition-transform hover:scale-105'>
                <UBadge class="absolute top-[-1dvw] right-[-1dvw]
                 h-4 sm:h-8 sm:text-lg text-[10px] bg-red-700" variant="">SALE</UBadge>
                <div class="flex h-[12dvw] ">
                  <div class="h-full w-full ">
                    <img src="/pcisco.jpeg" class="rounded-md  h-full w-screen" >
                  </div>
                </div>
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

            <div class="mb-5 ">
              <div class='relative object-cover rounded-md  mx-2 transition-transform hover:scale-105'>
                <UBadge class="absolute top-[-1dvw] right-[-1dvw]
                 h-4 sm:h-8 sm:text-lg text-[10px] bg-red-700" variant="">SALE</UBadge>
                <div class="flex h-[12dvw] ">
                  <div class="h-full w-full ">
                    <img src="/pcisco.jpeg" class="rounded-md  h-full w-screen" >
                  </div>
                </div>
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

            <div class="mb-5 ">
              <div class='relative object-cover rounded-md  mx-2 transition-transform hover:scale-105'>
                <UBadge class="absolute top-[-1dvw] right-[-1dvw]
                 h-4 sm:h-8 sm:text-lg text-[10px] bg-red-700" variant="">SALE</UBadge>
                <div class="flex h-[12dvw] ">
                  <div class="h-full w-full ">
                    <img src="/pcisco.jpeg" class="rounded-md  h-full w-screen" >
                  </div>
                </div>
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

            <div class="mb-5 ">
              <div class='relative object-cover rounded-md  mx-2 transition-transform hover:scale-105'>
                <UBadge class="absolute top-[-1dvw] right-[-1dvw]
                 h-4 sm:h-8 sm:text-lg text-[10px] bg-red-700" variant="">SALE</UBadge>
                <div class="flex h-[12dvw] ">
                  <div class="h-full w-full ">
                    <img src="/pcisco.jpeg" class="rounded-md  h-full w-screen" >
                  </div>
                </div>
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

            <div class="mb-5 ">
              <div class='relative object-cover rounded-md  mx-2 transition-transform hover:scale-105'>
                <UBadge class="absolute top-[-1dvw] right-[-1dvw]
                 h-4 sm:h-8 sm:text-lg text-[10px] bg-red-700" variant="">SALE</UBadge>
                <div class="flex h-[12dvw] ">
                  <div class="h-full w-full ">
                    <img src="/pcisco.jpeg" class="rounded-md  h-full w-screen" >
                  </div>
                </div>
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
        </div>
      </UCard> <div class="h-[6dvw] py-1 w-full ">

      <div class="h-full w-full cursor-pointer">
        <img src="/shoppee.png" class="rounded-md  sm:h-full w-full " >
      </div>
    </div>
    </template>



  </UTabs>
</template>

