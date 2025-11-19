<script setup>
import agent from '@/assets/images/why-auth0.png';
import ronnie from '@/assets/images/Ronnie-pic.webp';
import powell from '@/assets/images/phillipPowell.webp';
import sarah from '@/assets/images/sarah.webp';
import taiy from '@/assets/images/taiy.webp';
import kedrick from '@/assets/images/kedrick.jpg';

import lucas from '@/assets/images/lucas.webp';
import chantre from '@/assets/images/chantre.webp';
// import stephen from '@/assets/images/stephen.jpg';
// import james from '@/assets/images/James.jpg';
// import natasha from '@/assets/images/Natasha.jpg';
</script>

<template>
  <div class="py-20 bg-black text-white border-b">
    <div class="w-[80%] mx-auto">
      <div class="text-center w-full pb-10">
        <h3 class="text-3xl py-4">Agent</h3>
        <p class="text-xl">Listings Of Skyline Agents</p>
      </div>
      <div class="grid lg:grid-cols-3 gap-2">
        <!-- -------------Powell -->
        <div
          class="border bg-white rounded-xl p-2 shadow-xl text-black h-[600px] overflow-hidden drop-shadow-xl"
        >
          <div class="w-full h-[85%] bg-red-400">
            <img
              :src="powell"
              alt="Powell"
              class="w-full h-full object-cover duration-500 ease-in-out hover:scale-[1.09]"
            />
          </div>
          <h5 class="text-2xl pt-4">Phillip Powell</h5>
          <p class="text-lg">Commercial Agent</p>
        </div>
        <!-- -------------ROnnie -->
        <div
          class="border bg-white rounded-xl p-2 shadow-xl text-black h-[600px] overflow-hidden drop-shadow-xl"
        >
          <div class="w-full h-[85%] bg-red-400">
            <img
              :src="ronnie"
              alt="Ronnie"
              class="w-full h-full object-cover duration-500 ease-in-out hover:scale-[1.09]"
            />
          </div>
          <h5 class="text-2xl pt-4">Ronnie T. Clark</h5>
          <p class="text-lg">Commercial Agent</p>
        </div>

        <!-- -----------------Saarah -->
        <div
          class="border bg-white rounded-xl p-2 shadow-xl text-black h-[600px] overflow-hidden drop-shadow-xl"
        >
          <div class="w-full h-[85%] bg-red-400">
            <img
              :src="sarah"
              alt="Sarah Moudry"
              class="w-full h-full object-cover duration-500 ease-in-out hover:scale-[1.09]"
            />
          </div>
          <h5 class="text-2xl pt-4">Sarah Moudry</h5>
          <p class="text-lg">Sales</p>
        </div>
        <!-- -----------------taiye -->
        <div
          class="border bg-white rounded-xl p-2 shadow-xl text-black h-[600px] overflow-hidden drop-shadow-xl"
        >
          <div class="w-full h-[85%] bg-red-400">
            <img
              :src="taiy"
              alt="Santa Taiye"
              class="w-full h-full object-cover duration-500 ease-in-out hover:scale-[1.09]"
            />
          </div>
          <h5 class="text-2xl pt-4">Santa Taiye</h5>
          <p class="text-lg">Commercial Agent</p>
        </div>

        <!-- -------------Kedrick -->
        <div
          class="border bg-white rounded-xl p-2 shadow-xl text-black h-[600px] overflow-hidden drop-shadow-xl"
        >
          <div class="w-full h-[85%] bg-red-400">
            <img
              :src="kedrick"
              alt="kendrick Anderson"
              class="w-full h-full object-cover duration-500 ease-in-out hover:scale-[1.09]"
            />
          </div>
          <h5 class="text-2xl pt-4">Kendrick Anderson</h5>
          <p class="text-lg">Listing Agent</p>
        </div>

        <!-- ------------Graysean -->
        <div
          class="border bg-white rounded-xl p-2 shadow-xl text-black h-[600px] overflow-hidden drop-shadow-xl"
        >
          <div class="w-full h-[85%] bg-red-400">
            <img
              :src="stephen"
              alt="Graysean Bradley"
              class="w-full h-full object-cover duration-500 ease-in-out hover:scale-[1.09]"
            />
          </div>
          <h5 class="text-2xl pt-4">Graysean Bradley</h5>
          <p class="text-lg">Listing Agent</p>
        </div>

        <!-- ---------------------------Micheal -->
        <div
          class="border bg-white rounded-xl p-2 shadow-xl text-black h-[600px] overflow-hidden drop-shadow-xl"
        >
          <div class="w-full h-[85%] bg-red-400">
            <img
              :src="jame"
              alt="Micheal Crawford"
              class="w-full h-full object-cover duration-500 ease-in-out hover:scale-[1.09]"
            />
          </div>
          <h5 class="text-2xl pt-4">Micheal Crawford</h5>
          <p class="text-lg">Property Agent</p>
        </div>
        <!-- ---------------------------chantre-->
        <div
          class="border bg-white rounded-xl p-2 shadow-xl text-black h-[600px] overflow-hidden drop-shadow-xl"
        >
          <div class="w-full h-[85%] bg-red-400">
            <img
              :src="chantre"
              alt="Chantre Wright"
              class="w-full h-full object-cover duration-500 ease-in-out hover:scale-[1.09]"
            />
          </div>
          <h5 class="text-2xl pt-4">Chantre Wright</h5>
          <p class="text-lg">Listing Agent</p>
        </div>


        <!------------------Donnellius Grynn King------------->
           <div
          class="border bg-white rounded-xl p-2 shadow-xl text-black h-[600px] overflow-hidden drop-shadow-xl"
        >
          <div class="w-full h-[85%] bg-red-400">
            <img
              :src="james"
              alt="Donnellius G. Morris"
              class="w-full h-full object-cover duration-500 ease-in-out hover:scale-[1.09]"
            />
          </div>
          <h5 class="text-2xl pt-4">Donnellius Grynn King</h5>
          <p class="text-lg">Property Agent</p>
        </div>
        <!-- ---------------------------lucas-->
        <div
          class="border bg-white rounded-xl p-2 shadow-xl text-black h-[600px] overflow-hidden drop-shadow-xl"
        >



          <!------------------John Carter------------->
           <div
          class="border bg-white rounded-xl p-2 shadow-xl text-black h-[600px] overflow-hidden drop-shadow-xl"
        >
          <div class="w-full h-[85%] bg-red-400">
            <img
              :src="jams"
              alt="John Carter"
              class="w-full h-full object-cover duration-500 ease-in-out hover:scale-[1.09]"
            />
          </div>
          <h5 class="text-2xl pt-4">John Carter</h5>
          <p class="text-lg">Property Agent</p>
        </div>

           <!------------------Micheal Cooper------------->
           <div
          class="border bg-white rounded-xl p-2 shadow-xl text-black h-[600px] overflow-hidden drop-shadow-xl"
        >
          <div class="w-full h-[85%] bg-red-400">
            <img
              :src="jams"
              alt="Micheal Cooper"
              class="w-full h-full object-cover duration-500 ease-in-out hover:scale-[1.09]"
            />
          </div>
          <h5 class="text-2xl pt-4">Micheal Cooper</h5>
          <p class="text-lg">Property Agent</p>
        </div>


          <div class="w-full h-[85%] bg-red-400">
            <img
              :src="lucas"
              alt="lucas freeman"
              class="w-full h-full object-cover duration-500 ease-in-out hover:scale-[1.09]"
            />
          </div>
          <h5 class="text-2xl pt-4">Lucas Freeman</h5>
          <p class="text-lg">Listing Agent</p>
        </div>
      </div>
    </div>
  </div>
</template>
