<template>
       <div class="w-full">
        <div class="max-w-2xl mx-auto rounded-lg lg:p-8">
            <div class="flex gap-2 items-center justify-between max-w-lg">
                <div class="flex items-center">
                    <img src="https://i.ibb.co/8PwcSQN/Group-1073714856.png" class="h-[80%]"/>
                <h1 class="text-3xl font-bold text-left text-gradient mb-4">Get Started</h1>
                </div>
                <div>
                    <p class="text-gradient font-bold">You earned 20 500</p>
                    <p class="text-gray ">Total XP to earn : 12 000</p>
                </div>
            </div>
            <div>
                <div class="shadow-lg bg-white rounded-lg max-w-lg h-[15px] relative flex items-center mb-6">
                    <div class=" ml-2 shadow-lg rounded-lg w-[50%] h-[7px]" style="background: linear-gradient(90deg, #40BEBE, #2361E6)"></div>
                </div>
            </div>
        <div class="bg-white rounded-lg shadow-lg max-w-lg w-full p-4">
            <div
            class="bg-gradient-to-r from-[#F0F0FB]  to-[#F0F0FB] max-w-sm rounded-lg mx-[30px] p-8">
            <h4 class="text-#25213E font-medium">Inbox Name</h4>
            <button class="bg-white rounded-lg w-full text-left p-3 my-2 font-medium">
                VivaTech
            </button>
            <div>
                <h4 class="text-#25213E font-medium">Inbox Color</h4>
            <div class="flex space-x-1 mt-2 gap-4 ">
                <div v-for="(color, index) in InboxIconColor" :key="index" class="relative group">
    <svg class="hover:scale-150 group-hover:opacity-100" id='Inbox_24' width='30' height='30' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'>
      <rect width='35' height='35' stroke='none' :fill='color' opacity='0'/>
      <g transform="matrix(0.91 0 0 0.91 12 12)">
        <path :style="{ fill: color }"
              style="stroke: none; stroke-width: 1; stroke-dasharray: none; stroke-linecap: butt; stroke-dashoffset: 0; stroke-linejoin: miter; stroke-miterlimit: 4;  fill-rule: nonzero; opacity: 1;"
              transform="translate(-15, -15)"
              d="M 7.8671875 4 C 6.8792418 4 6.0274565 4.7395617 5.8867188 5.7167969 L 4.0097656 18.859375 C 4.003206834096734 18.905961956444163 3.9999435301649116 18.95295365336116 4 19 L 4 24 C 4 25.093063 4.9069372 26 6 26 L 24 26 C 25.093063 26 26 25.093063 26 24 L 26 19 C 26.000056337321176 18.952953643930552 25.996792899720887 18.90596194696756 25.990234 18.859375 L 24.111328 5.71875 L 24.111328 5.7167969 C 23.971587 4.7390631 23.120167 4 22.132812 4 L 7.8671875 4 z M 7.8671875 6 L 22.132812 6 L 23.990234 19 L 17.816406 19 C 17.403406 20.163 16.304 21 15 21 C 13.696 21 12.596594 20.163 12.183594 19 L 6.0097656 19 L 7.8671875 6.0019531 L 7.8671875 6 z"
              stroke-linecap="round" />
      </g>
    </svg>
    <div class="flex bg-white rounded-lg  items-start absolute shadow-md top-[-170px] left-[-60px] w-72 transform -translate-y-12 opacity-0 group-hover:translate-y-0 group-hover:opacity-100 transition-all duration-300">
      <div class="ml-4 relative bg-white w-72 p-4 rounded-lg ">
        <button :style="{ backgroundColor: color }" class="flex shadow items-center justify-center gap-2 text-white font-medium py-2 px-4 rounded-full">
          <svg cid='Inbox_24' width='20' height='20' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'>
            <rect width='24' height='24' stroke='none' fill='#ffffff' opacity='0'/>
            <g transform="matrix(0.91 0 0 0.91 12 12)">
              <path style="stroke: none; stroke-width: 1; stroke-dasharray: none; stroke-linecap: butt; stroke-dashoffset: 0; stroke-linejoin: miter; stroke-miterlimit: 4; fill: #ffffff; fill-rule: nonzero; opacity: 1;" transform=" translate(-15, -15)" d="M 7.8671875 4 C 6.8792418 4 6.0274565 4.7395617 5.8867188 5.7167969 L 4.0097656 18.859375 C 4.003206834096734 18.905961956444163 3.9999435301649116 18.95295365336116 4 19 L 4 24 C 4 25.093063 4.9069372 26 6 26 L 24 26 C 25.093063 26 26 25.093063 26 24 L 26 19 C 26.000056337321176 18.952953643930552 25.996792899720887 18.90596194696756 25.990234 18.859375 L 24.111328 5.71875 L 24.111328 5.7167969 C 23.971587 4.7390631 23.120167 4 22.132812 4 L 7.8671875 4 z M 7.8671875 6 L 22.132812 6 L 23.990234 19 L 17.816406 19 C 17.403406 20.163 16.304 21 15 21 C 13.696 21 12.596594 20.163 12.183594 19 L 6.0097656 19 L 7.8671875 6.0019531 L 7.8671875 6 z" stroke-linecap="round" />
            </g>
          </svg>
          VivaTech
        </button>
        <div class=" mt-2 text-gray-700">
          Hello <span class="font-semibold">{FirstName}</span>, It was a pleasure to meet you at Vivatech.
        </div>
        <div class="absolute shadow-md rounded  transform -translate-x-1/2 bottom-[-25px] w-8 h-24 bg-white rotate-45 -z-10 left-[80px]"></div>
      </div>

    </div>

  </div>

         </div>

</div>
            </div>

<div class="mt-4 flex items-center justify-between">
    <div class="flex items-center space-x-2">
        <input type="checkbox" checked class="form-checkbox h-6 w-6 rounded-['100%'] text-transparent  border focus:ring-0">
        <h2 class="text-lg font-medium text-gray-800"><del>Create more inbox</del></h2>
    </div>
    <div class="text-blue-500 text-sm font-medium">+500 XP</div>
</div>
<p class="text-sm text-gray-500 mt-2">Create more inbox, welcome your new contact by a message</p>
</div>

        <div class="bg-white rounded-lg shadow-lg max-w-lg w-full p-4 mt-6">

        <div class="relative">
            <img class="w-full h-48 object-cover rounded-lg" src="https://i.ibb.co/nrgk2g7/Rectangle-921719.png" alt="Thumbnail">
            <div class="absolute  inset-0  flex items-center justify-center">
                <button class="rounded-full" style="background-color: rgba(186, 186, 186, 0.4); box-shadow: inset -2px -2px 2.5px rgba(255, 255, 255, 0.5), inset 2px 2px 6.8px rgba(255, 255, 255, 0.3);">
                <svg class="w-12 h-12 text-white" fill="currentColor" viewBox="0 0 24 24" >
                    <path d="M10 17l6-5-6-5v10z" />
                </svg>
            </button>
            </div>
        </div>
        <div class="mt-4 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <input type="checkbox" class="form-checkbox h-6 w-6 rounded-['100%'] text-transparent  border focus:ring-0">
                <h2 class="text-lg font-medium text-gray-800">Manage your messaging rules</h2>
            </div>
            <div class="text-blue-500 text-sm font-medium">+100 XP</div>
        </div>
        <p class="text-sm text-gray-500 mt-2">Create more inbox, welcome your new contact by a message</p>
    </div>
    </div>
       </div>
  </template>

<script setup>
    import { ref } from 'vue'
    const InboxIconColor = ref(['#DB4CF4','#8057EC','#2864ED','#10BBE0','#EF3A00','#EFBB00','#93ADB2']);

</script>

<style scope>
.text-gradient {
    background: linear-gradient(90deg, #40BEBE, #2361E6);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    color: transparent;
  }
input[type="checkbox"] {
            appearance: none;
            -webkit-appearance: none;
            -moz-appearance: none;
            width: 24px;
            height: 24px;
            border-radius: 50%;
            border: 2px solid transparent;
            background: linear-gradient(white, white) padding-box, linear-gradient(90deg, #40BEBE 0%, #2361E6 100%) border-box;
            cursor: pointer;
        }
        input[type="checkbox"]:checked {
            background: linear-gradient(90deg, #40BEBE 0%, #2361E6 100%);
            border:none;
        }
        input[type="checkbox"]:checked::before {
            content: '\2713'; /* Unicode character for checkmark */
            display: block;
            text-align: center;
            color: white;
            font-weight: bold;
            font-size: 16px;
            line-height: 24px;
        }
</style>

