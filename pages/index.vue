<template>
  <div class="bg-white ">

    <div class=" ">
      <div class="h-[20dvw] border-2  ">
        <CarouselNav/>
      </div>
    </div>

    <div class="bg-white  sm:px-14 px-1 sm:pt-5 pt-4 sm:h-[98dvw] lg:h-[82dvw] xl:h-[67dvw] 2xl:h-[55dvw]">
      <LogoRoute/>
      <div class="">

        <div class="grid sm:grid-cols-2 grid-cols-1  sm:space-x-5 py-5">
            <div class=" h-full ">
              <UDivider
                  label="HOT SALE" class=""
                        :ui="{ label: 'text-rose-500 dark:text-error-500 font-bold text-xl', line: 'bg-green-500' }"
              />

              <div class="flex items-center justify-center  ">
                <HotSale/>
              </div>
            </div>

            <div class="flex flex-col sm:mt-0 mt-14  sm:h-full  w-full ">
              <div class="mb-5 w-full lg:h-1/2 ">
                  <UDivider
                      label="NEWS" class=""
                      :ui="{ label: 'text-rose-500 dark:text-error-500 font-bold text-xl', line: 'bg-green-500' }"
                  />
                <div class="h-full">
                  <CarouselNew/>
                </div>
              </div>

              <div class="w-full h-1/2 lg:h-full ">
                <UDivider
                    label="TOP PRODUCT" class=""
                    :ui="{ label: 'text-rose-500 dark:text-error-500 font-bold text-xl', line: 'bg-green-500' }"
                />
                <div class="h-full ">
                  <TopProduct/>
                </div>
              </div>
            </div>
        </div>
      </div>

    </div>

    <div class="w-full ">
      <div class="  sm:mx-9  sm:ml-14 mb-3">
        <div class="grid sm:grid-cols-2 grid-cols-1  lg:h-full ">
          <div class=" rounded-md mr-3 bor-slate-900 border-2 border-green-700 px-2">
            <Faq/>
          </div>

          <div class=" h-full py-2 rounded-md ml-3 border-2 border-green-700 text-sm">
            <Contact/>
          </div>

        </div>
      </div>
    </div>

  </div>
</template>
<script setup lang="ts">
import CarouselNav from "~/components/index/CarouselNav.vue";
import LogoRoute from "~/components/index/LogoRoute.vue";
import HotSale from "~/components/index/HotSale.vue";
import CarouselNew from "~/components/index/CarouselNew.vue";
import  TopProduct from "~/components/index/TopProduct.vue";
import Contact from "~/components/index/Contact.vue";
import Faq from "~/components/index/Faq.vue";

const items = [{
  key: 'account',
  label: 'Account',
  description: 'Make changes to your account here. Click save when you\'re done.'
}, {
  key: 'password',
  label: 'Password',
  description: 'Change your password here. After saving, you\'ll be logged out.'
}]

</script>