<template>
  <div class="m-2  flex items-center  space-x-2 ">
    <img src='/sslogo.png' class="w-14">
    <h1 class="lg:text-xl">บริษัท เอส แอนด์ เอส แอชโซซิเอชั่น จำกัด</h1>
  </div>
  <div class="mx-2 ">
    <hr class="border-green-700 border-2 "/>
  </div>
  <div class="mx-2 mt-3 ">
    <p class="mt5">ติดต่อสอบถามข้อมูล หรือสั่งสินค้าจำมากกรุณากรอกแบบฟอร์มส่ง E-Mail </p>

    <div class="flex justify-between items-center gap-5 my-4">
      <div class="w-full space-y-2">
        <h1>ชื่อจริง</h1>
        <UInput placeholder="กรุณากรอกชื่อจริงของคุณ"/>
      </div>
      <div class="w-full space-y-2">
        <h1>นามสกุล</h1>
        <UInput placeholder="กรุณากรอกชื่อนามสกุลของคุณ"/>
      </div>
    </div>

    <div class="flex  items-center gap-5 my-4">
      <div class="w-full ">
        <h1 class="">หัวข้อ</h1>
        <UInput placeholder="กรุณากรอกหัวข้อของคุณ"/>
      </div>
    </div>

    <div class="flex  items-center gap-5 my-4">
      <div class="w-full ">
        <h1 class="">ข้อความ</h1>
        <UTextarea color="white" variant="outline" placeholder="Search..." />
      </div>
    </div>

    <div class='flex items-center justify-center  rounded-md
            space-x-2 transition-transform hover:scale-105 w-full'>
      <button  class="w-full bg-red-700 text-white rounded-md h-10 mx-2">ยืนยันส่ง E-MAIL</button>
    </div>

  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>