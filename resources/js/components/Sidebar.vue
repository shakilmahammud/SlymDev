<template>

  <div class="w-80 bg-white rounded-lg shadow-lg p-4">
    <div class="flex justify-between items-center">
      <h2 class="text-lg font-semibold"
     >DM Setting</h2>
      <button class="text-gray-400 border-2  rounded-lg w-[48px] h-[48px]">&times;</button>
    </div>
    <div class="my-4">
      <button class="flex items-center justify-between w-full py-2 px-2 bg-blue-100 rounded-lg hover:bg-blue-200">
       <div class="flex">
        <img src="https://i.ibb.co/8PwcSQN/Group-1073714856.png"/>
        <span class="font-semibold text-gradient" >DM Tour Guide</span>
       </div>

        <div class="bg-white p-1 rounded-full relative">
            <div class="progress">
                <p class="font-medium p-1"><span class="text-[#2361E6] ">4</span><span class="text-[#B6BABF]">/8</span></p>

            </div>
        </div>
      </button>
    </div>
    <div class="space-y-4">
      <h3 class="font-semibold">Manage Inbox</h3>
      <div class="space-y-2">
        <button class="flex items-center space-x-2 w-full py-2 px-4 hover:bg-gray-100 rounded-lg">
            <img src="https://i.ibb.co/fr6VS8L/inbox-01.png"/>
            <span>Inbox</span>
        </button>
        <button class="flex items-center space-x-2 w-full py-2 px-4 hover:bg-gray-100 rounded-lg">
            <img src="https://i.ibb.co/J2TB9Q7/Group-1073715282.png"/>
            <span>Discussion Rules</span>
        </button>
        <button class="flex items-center space-x-2 w-full py-2 px-4 hover:bg-gray-100 rounded-lg">
            <svg id='Single_Neutral_Book_24' width='24' height='24' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'><rect width='24' height='24' stroke='none' fill='gray' opacity='0'/>
            <g transform="matrix(0.83 0 0 0.83 12 12)" >
            <g style="" >
            <g transform="matrix(1 0 0 1 0 0)" >
            <path style="stroke: gray; stroke-width: 1; stroke-dasharray: none; stroke-linecap: round; stroke-dashoffset: 0; stroke-linejoin: round; stroke-miterlimit: 4; fill: none; fill-rule: nonzero; opacity: 1;" transform=" translate(-12, -12)" d="M 20 0.5 L 4.5 0.5 C 3.6715728752538097 0.5 3 1.1715728752538097 3 2 C 3 2.8284271247461903 3.6715728752538097 3.5 4.5 3.5 L 20.5 3.5 C 20.7761423749154 3.5 21 3.7238576250846034 21 4 L 21 23 C 21 23.2761423749154 20.7761423749154 23.5 20.5 23.5 L 5 23.5 C 3.895430500338413 23.5 3 22.604569499661586 3 21.5 L 3 2" stroke-linecap="round" />
            </g>
            <g transform="matrix(1 0 0 1 0.5 5)" >
            <path style="stroke: gray; stroke-width: 1; stroke-dasharray: none; stroke-linecap: round; stroke-dashoffset: 0; stroke-linejoin: round; stroke-miterlimit: 4; fill: none; fill-rule: nonzero; opacity: 1;" transform=" translate(-12.5, -17)" d="M 17.5 19.5 C 17.5 16.738576250846034 15.261423749153966 14.5 12.5 14.5 C 9.738576250846034 14.5 7.5 16.738576250846034 7.5 19.5 Z" stroke-linecap="round" />
            </g>
            <g transform="matrix(1 0 0 1 0.5 -2)" >
            <path style="stroke: gray; stroke-width: 1; stroke-dasharray: none; stroke-linecap: round; stroke-dashoffset: 0; stroke-linejoin: round; stroke-miterlimit: 4; fill: none; fill-rule: nonzero; opacity: 1;" transform=" translate(-12.5, -10)" d="M 9.5 10 C 9.5 11.65685424949238 10.84314575050762 13 12.5 13 C 14.15685424949238 13 15.5 11.65685424949238 15.5 10 C 15.5 8.34314575050762 14.15685424949238 7 12.5 7 C 10.84314575050762 7 9.5 8.343145750507619 9.5 10 Z" stroke-linecap="round" />
            </g>
            </g>
            </g>
            </svg>
          <span>Address Book</span>
        </button>
        <button class="flex items-center space-x-2 w-full py-2 px-4 hover:bg-gray-100 rounded-lg">
            <img src="https://i.ibb.co/rkB0M4G/Group.png"/>
            <span>Zapier</span>
        </button>
      </div>
    </div>
    <div class="space-y-4 mt-6">
      <h3 class="font-semibold">Advanced Messages</h3>
      <div class="space-y-2">
        <div class="flex items-center space-x-2 w-full py-2 px-4 rounded-lg">
          <img src="https://i.ibb.co/DrzQ6yP/boostDM.png"/>
          <span>Boost DM</span>
          <span class="ml-auto text-gray-400">Coming Soon..</span>
        </div>
        <div class="flex items-center space-x-2 w-full py-2 px-4 rounded-lg">
          <img src="https://i.ibb.co/xXSqkDD/Blurred-DM.png"/>
          <span>Blurred DM</span>
          <span class="ml-auto text-gray-400">Coming Soon..</span>
        </div>
      </div>
    </div>
  </div>
  </template>

  <<style scoped>
   .text-gradient {
    background: linear-gradient(90deg, #40BEBE, #2361E6);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    color: transparent;
  }
  .progress{
    appearance: none;
            -webkit-appearance: none;
            -moz-appearance: none;
            width: 100%;
            height: 100%;
            border-radius: 50%;
            border: 3px solid transparent;
            background:  linear-gradient(white, white) padding-box,
            linear-gradient(90deg, #40BEBE 0, #2361E6 50%, #ccc 50%, #ccc 100%) border-box;
  }

  </style>
