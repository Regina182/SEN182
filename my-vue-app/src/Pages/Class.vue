<script setup>
</script>


<template>



<div class="w-screen h-100 bg-[#0F1629] text-white p-6 ">
    
<div class="flex justify-center">
  <div class="flex items-center  bg-[#1E253B] rounded-lg p-4 w-full max-w-6xl h-16">
    <div class="flex items-center w-full">
      <div class="flex items-center flex-1">
        <img src="../assets/logo.svg" alt="Extensions Icon" class="w-20 h-20" />
        <span class="text-white font-medium text-lg">Extensions</span>
      </div>
      
      <div class="ml-auto">
        <button class="bg-[#2C3552] p-2 rounded-md transition">
          <img src="../assets/icon-sun.svg" alt="Theme Toggle Icon" class="w-6 h-6" />
        </button>
      </div>
    </div>
  </div>
  </div>

<div class="mt-6 max-w-5xl mx-auto flex flex-col justify-center gap-3 items-center lg:flex-row lg:justify-between">
  <h2 class="text-2xl font-bold lg:mr-auto">Extensions List</h2>
  <div class="flex gap-3 lg:ml-auto">
    <button class="bg-red-500 text-white px-4 py-1 rounded-full font-regular text-sm ">All</button>
    <button class="bg-gray-700 text-white px-4 py-1 rounded-full font-regular text-sm ">Active</button>
    <button class="bg-gray-700 text-white px-4 py-1 rounded-full font-regular text-sm ">Inactive</button>
  </div>
</div>


<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-x-2 gap-y-2 mt-8 max-w-6xl mx-auto text-regular">
    
    <div class="bg-[#1E253B] p-5 rounded-xl border border-gray-700 w-50 h-50 flex flex-col justify-between">
      <div class="flex items-start gap-4">
        <div class="rounded-md flex items-center justify-center">
          <img src="../assets/logo-devlens.svg" alt="DevLens Icon" class="w-15 h-15" />
        </div>
        <div>
          <h3 class=" text-white text-left font-semibold">DevLens</h3>
          <p class="text-sm text-left text-gray-300 mt-1 font-light ">Quickly inspect page layouts and <br>visualize element boundaries.</p>
        </div>
      </div>

     <div class="flex justify-between items-center mt-6">
        <button class="bg-gray-700 border-solid border-slate-300 mt-5 px-3 py-1 rounded-full text-xs font-light text-white ">Remove</button>
        <div class="w-10 h-5 bg-red-500 mt-5 rounded-full relative">
          <div class="w-4 h-4 bg-white rounded-full absolute top-0.5 left-0.5 translate-x-5 transition-transform"></div>
        </div>
      </div>
    </div>


    <div class="bg-[#1E253B] p-5 rounded-xl border border-gray-700 w-50 h-50 flex flex-col justify-between">
      <div class="flex items-start gap-4">
        <div class="rounded-md flex items-center justify-center">
          <img src="../assets/logo-style-spy.svg" alt="StyleSpy Icon" class="w-14 h-14"/>
        </div>
        <div>
          <h3 class=" text-white text-left font-semibold">StyleSpy</h3>
          <p class="text-sm text-left text-gray-300 mt-1 font-light">Instantly analyze and copy CSS from <br> any webpage element.</p>
        </div>
      </div>

      <div class="flex justify-between items-center mt-6">
        <button class="bg-gray-700 border-solid border-slate-300 mt-6 px-3 py-1 rounded-full text-xs font-light text-white ">Remove</button>
        <div class="w-10 h-5 bg-red-500 mt-5 rounded-full relative">
          <div class="w-4 h-4 bg-white rounded-full absolute top-0.5 left-0.5 translate-x-5 transition-transform"></div>
        </div>
      </div>
    </div>


    
    <div class="bg-[#1E253B] p-5 rounded-xl border border-gray-700 w-50 h-50 flex flex-col justify-between">
      <div class="flex items-start gap-4">
        <div class="w-15 h-15  rounded-md flex items-center justify-center">
          <img src="../assets/logo-speed-boost.svg" alt="SpeedBoost Icon" class="w-14 h-14"  />
        </div>
        <div>
          <h3 class=" text-white text-left font-semibold">SpeedBoost</h3>
          <p class="text-sm text-left text-gray-300 mt-1 font-light">Optimizes browser resource usage to accelerate page loading.</p>
        </div>
      </div>
      <div class="flex justify-between items-center mt-6">
        <button class="bg-gray-700  border-solid border-slate-300 mt-5 px-3 py-1 rounded-full  font-light text-xs text-white ">Remove</button>
        <div class="w-10 h-5 bg-gray-600 mt-5 rounded-full relative">
          <div class="w-4 h-4 bg-white rounded-full absolute top-0.5 left-0.5  "></div>
        </div>
      </div>
    </div>


    <div class="bg-[#1E253B] p-5 rounded-xl border border-gray-700 w-50 h-50  flex flex-col justify-between">
      <div class="flex items-start gap-4">
        <div class=" w-15 h-15 rounded-md flex items-center justify-center">
          <img src="../assets/logo-json-wizard.svg" alt="StyleSpy Icon"  class="w-14 h-14" />
    
        </div>
        <div>
          <h3 class=" text-white text-left font-semibod">JsonWizard</h3>
          <p class="text-sm text-left text-gray-300 mt- font-light ">Formats, validates, and prettifies <br>JSON responses in-brower. </p>
        </div>
      </div>
      <div class="flex justify-between items-center mt-6">
        <button class="bg-gray-700  border-solid border-slate-300 mt-5 px-3 py-1 rounded-full text-xs text-white font-light">Remove</button>
        <div class="w-10 h-5 bg-red-500 mt-5 rounded-full relative">
          <div class="w-4 h-4 bg-white rounded-full absolute top-0.5 left-0.5 translate-x-5 transition-transform"></div>
        </div>
      </div>
    </div>

    <div class="bg-[#1E253B] p-5 rounded-xl border border-gray-700 w-50 h-50 flex flex-col justify-between">
      <div class="flex items-start gap-4">
        <div class=" w-15 h-15 rounded-md flex items-center justify-center">
          <img src="../assets/logo-tab-master-pro.svg" alt="StyleSpy Icon"  class="w-11 h-11"  />
        </div>
        <div>
          <h3 class=" text-white text-left  font-semibold">TabMaster Pro</h3>
          <p class="text-sm text-left text-gray-300 mt-1  font-light">Organises browser tabs into groups <br> and sessions</p>
        </div>
      </div>
      <div class="flex justify-between items-center mt-6">
        <button class="bg-gray-700  border-solid border-slate-300 mt-5 px-3 py-1 rounded-full font-light text-xs text-white ">Remove</button>
        <div class="w-10 h-5 bg-red-500 mt-5 rounded-full relative">
          <div class="w-4 h-4 bg-white rounded-full absolute top-0.5 left-0.5 translate-x-5 transition-transform"></div>
        </div>
      </div>
    </div>

    <div class="bg-[#1E253B] p-5 rounded-xl border border-gray-700 w-50 h-50 flex flex-col justify-between">
      <div class="flex items-start gap-4">
        <div class=" w-15 h-15 rounded-md flex items-center justify-center">
          <img src="../assets/logo-viewport-buddy.svg" alt="SpeedBoost Icon" class="w-14 h-14" />
        </div>
        <div>
          <h3 class=" text-white text-left font-semibold">ViewportBuddy</h3>
          <p class="text-sm text-left text-gray-300 mt-1 font-light ">Simulates various screen resolutions <br> directly within the browser.</p>
        </div>
      </div>
      <div class="flex justify-between items-center mt-6">
        <button class="bg-gray-700  border-solid border-slate-300 mt-5 px-3 py-1 rounded-full text-xs text-white ">Remove</button>
        <div class="w-10 h-5 bg-gray-600 mt-5 rounded-full relative">
          <div class="w-4 h-4 bg-white rounded-full absolute top-0.5 left-0.5  "></div>
        </div>
      </div>
    </div>
    
    <div class="bg-[#1E253B] p-5 rounded-xl border border-gray-700 w-50 h-50  flex flex-col justify-between">
      <div class="flex items-start gap-4">
        <div class="w-15 h-15 rounded-md flex items-center justify-center">
          <img src="../assets/logo-markup-notes.svg" alt="StyleSpy Icon"   class="w-20 h-20 "  />
         
        </div>
        <div>
          <h3 class=" text-white text-left font-semibold">Markup Notes</h3>
          <p class="text-sm text-left text-gray-300 mt-1 font-light">Enables annotation and notes directly  onto webpages for collaborative <br> debugging </p>
        </div>
      </div>
      <div class="flex justify-between items-center mt-6">
        <button class="bg-gray-700  border-solid border-slate-300 mt-5 px-3 py-1 rounded-full text-xs font-light text-white ">Remove</button>
        <div class="w-10 h-5 bg-red-500 mt-5 rounded-full relative">
          <div class="w-4 h-4 bg-white rounded-full absolute top-0.5 left-0.5 translate-x-5 transition-transform"></div>
        </div>
      </div>
    </div>

     <div class="bg-[#1E253B] p-5 rounded-xl border border-gray-700 w-50 h-50 flex flex-col justify-between">
      <div class="flex items-start gap-4">
        <div class=" w-15 h-15 rounded-md flex items-center justify-center">
          <img src="../assets/logo-grid-guides.svg" alt="SpeedBoost Icon" class="w-15 h-15" />
        </div>
        <div>
          <h3 class=" text-white text-left  font-semibold">GridGuides</h3>
          <p class="text-sm text-left text-gray-300 mt-1 font-light ">Overlay customizable grids and <br> alignment guides on any 
            webpage.</p>
        </div>
      </div>
      <div class="flex justify-between items-center mt-6">
        <button class="bg-gray-700  border-solid border-slate-300  mt-5 px-3 py-1 rounded-full font-light text-xs text-white ">Remove</button>
        <div class="w-10 h-5 bg-gray-600 mt-5 rounded-full relative">
          <div class="w-4 h-4 bg-white rounded-full absolute top-0.5 left-0.5  "></div>
        </div>
      </div>
    </div>

    <div class="bg-[#1E253B] p-5 rounded-xl border border-gray-700 w-50 h-50 flex flex-col justify-between">
      <div class="flex items-start gap-4">
        <div class=" w-15 h-15 rounded-md flex items-center justify-center">
          <img src="../assets/logo-palette-picker.svg" alt="StyleSpy Icon" class="w-12 h-12"   />
        </div>
        <div>
          <h3 class=" text-white text-left font-semibold ">Palette Picker</h3>
          <p class="text-sm text-left text-gray-300 mt-1 font-light">Instantly extracts color palettes from  <br>
            any webpage.</p>
        </div>
      </div>
      <div class="flex justify-between items-center mt-6">
        <button class="bg-gray-700  border-solid border-slate-300 mt-5 px-3 py-1 rounded-full font-light text-xs text-white">Remove</button>
        <div class="w-10 h-5 bg-red-500 mt-5 rounded-full relative">
          <div class="w-4 h-4 bg-white rounded-full absolute top-0.5 left-0.5 translate-x-5 transition-transform"></div>
        </div>
      </div>
    </div>

    <div class="bg-[#1E253B] p-5 rounded-xl border border-gray-700 w-50 h-50  flex flex-col justify-between">
      <div class="flex items-start gap-4">
        <div class=" w-15 h-15 rounded-md flex items-center justify-center">
          <img src="../assets/logo-link-checker.svg" alt="StyleSpy Icon"  class="w-12 h-12"  />
        </div>
        <div>
          <h3 class=" text-white text-left font-semibold">LinkChecker</h3>
          <p class="text-sm text-left text-gray-300 mt-1 font-light "> Scans and highlights broken links on <br> any page.</p>
        </div>
      </div>
      <div class="flex justify-between items-center mt-6">
        <button class="bg-gray-700  border-solid border-slate-300 mt-5 px-3 py-1 rounded-full text-xs text-white font-light ">Remove</button>
        <div class="w-10 h-5 bg-red-500 mt-5 rounded-full relative">
          <div class="w-4 h-4 bg-white rounded-full absolute top-0.5 left-0.5 translate-x-5 transition-transform"></div>
        </div>
      </div>
    </div>
    

     <div class="bg-[#1E253B] p-5 rounded-xl border border-gray-700 w-50 h-50  flex flex-col justify-between">
      <div class="flex items-start gap-4">
        <div class=" w-15 h-15 rounded-md flex items-center justify-center">
          <img src="../assets/logo-dom-snapshot.svg" alt="SpeedBoost Icon" class="w-11 h-11"   />
        </div>
        <div>
          <h3 class=" text-white text-left font-semibold">DOM SnapShot</h3>
          <p class="text-sm text-left text-gray-300 mt-1 font-light ">Capture and export DOM structures <br> quickly.</p>
        </div>
      </div>
      <div class="flex justify-between items-center mt-6">
        <button class="bg-gray-700  border-solid border-slate-300 mt-5 px-3 py-1 rounded-full text-xs text-white  font-light">Remove</button>
        <div class="w-10 h-5 bg-gray-600 mt-5 rounded-full relative">
          <div class="w-4 h-4 bg-white rounded-full absolute top-0.5 left-0.5  "></div>
        </div>
      </div>
    </div>
     
     <div class="bg-[#1E253B] p-5 rounded-lg border border-gray-700 w-50 h-50 flex flex-col justify-between">
      <div class="flex items-start gap-4">
        <div class=" w-15 h-15 rounded-md flex items-center justify-center">
          <img src="../assets/logo-console-plus.svg" alt="StyleSpy Icon"   />
        </div>
        <div>
          <h3 class=" text-white text-left font-semibold">Consoleplus</h3>
          <p class="text-sm text-left text-gray-300 mt-1 font-light"> Enhanced developer console with <br> advanced filtering and logging.</p>
        </div>
      </div>
      <div class="flex justify-between items-center mt-6">
        <button class="bg-gray-700  border-solid border-slate-300 mt-5 px-3 py-1 rounded-full text-xs text-white font-light">Remove</button>
        <div class="w-10 h-5 bg-red-500 mt-5 rounded-full relative">
          <div class="w-4 h-4 bg-white rounded-full absolute top-0.5 left-0.5 translate-x-5 transition-transform"></div>
        </div>
      </div>
    </div>
    

</div>


</div>




  
  
 


</template> 