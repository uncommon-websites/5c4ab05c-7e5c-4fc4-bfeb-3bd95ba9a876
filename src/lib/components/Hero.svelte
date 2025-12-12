<script lang="ts">
  // Hero Section
</script>

<section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto flex flex-col items-center text-center">
  <h1 class="text-5xl md:text-7xl font-bold tracking-tight text-gray-900 max-w-4xl mb-8 leading-[1.1]">
    Create staff schedules in minutes with <span class="text-[oklch(0.588_0.158_241.966)]">AI-powered shift planning</span>
  </h1>

  <p class="text-xl text-gray-600 max-w-2xl mb-12">
    Stop wasting hours on manual scheduling. newRota matches worker availability with shift needs automatically.
  </p>

  <div class="flex flex-col sm:flex-row gap-4 mb-16">
    <button class="bg-[oklch(0.588_0.158_241.966)] text-white px-8 py-3 rounded-full text-lg font-medium hover:bg-[oklch(0.5_0.134_242.749)] transition-colors">
      Start free trial
    </button>
    <button class="bg-white text-gray-900 border border-gray-200 px-8 py-3 rounded-full text-lg font-medium hover:bg-gray-50 transition-colors flex items-center gap-2">
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-play-circle"><circle cx="12" cy="12" r="10"/><polygon points="10 8 16 12 10 16 10 8"/></svg>
      Watch demo
    </button>
  </div>

  <!-- Hero Image Placeholder (App Interface) -->
  <div class="w-full max-w-5xl bg-white rounded-xl shadow-2xl border border-gray-200 overflow-hidden relative aspect-[16/10] text-left">
    <!-- Fake Browser Header -->
    <div class="bg-gray-50 border-b border-gray-200 p-3 flex items-center gap-2">
      <div class="flex gap-1.5">
        <div class="w-3 h-3 rounded-full bg-red-400"></div>
        <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
        <div class="w-3 h-3 rounded-full bg-green-400"></div>
      </div>
      <div class="mx-auto text-xs text-gray-400 font-medium">Week Schedule - Downtown Gym</div>
    </div>
    
    <!-- App Content -->
    <div class="flex h-full">
      <!-- Sidebar -->
      <div class="w-64 border-r border-gray-100 bg-gray-50/50 p-4 hidden md:block">
        <div class="space-y-4">
          <div class="h-4 w-32 bg-gray-200 rounded"></div>
          <div class="space-y-2">
             <div class="h-8 w-full bg-[oklch(0.588_0.158_241.966)] text-white rounded-lg shadow-sm flex items-center px-3 text-xs font-medium">Downtown Gym</div>
             <div class="h-8 w-full bg-transparent rounded-lg flex items-center px-3 text-xs text-gray-600">Westside Location</div>
             <div class="h-8 w-full bg-transparent rounded-lg flex items-center px-3 text-xs text-gray-600">Eastside Location</div>
          </div>
        </div>
      </div>
      
      <!-- Main Content -->
      <div class="flex-1 p-8 bg-white">
        <div class="max-w-3xl mx-auto">
           <div class="flex justify-between items-center mb-6">
             <h2 class="text-2xl font-bold">Week of Jan 15-21</h2>
             <button class="bg-[oklch(0.588_0.158_241.966)] text-white px-4 py-2 rounded-lg text-sm font-medium">Publish Schedule</button>
           </div>
           
           <div class="space-y-4">
             <!-- Schedule Grid -->
             <div class="grid grid-cols-7 gap-2 text-xs">
               {#each ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun'] as day}
                 <div class="text-center font-medium text-gray-500">{day}</div>
               {/each}
             </div>
             
             <!-- Shift Cards -->
             <div class="space-y-3">
               <div class="bg-blue-50 border border-blue-200 rounded-lg p-3">
                 <div class="flex items-center justify-between mb-2">
                   <span class="font-medium text-sm">Morning Shift</span>
                   <span class="text-xs text-gray-500">6:00 AM - 2:00 PM</span>
                 </div>
                 <div class="flex items-center gap-2">
                   <div class="w-6 h-6 rounded-full bg-blue-400"></div>
                   <span class="text-sm text-gray-700">Sarah Johnson</span>
                   <span class="ml-auto text-xs bg-blue-100 text-blue-700 px-2 py-1 rounded">Front Desk</span>
                 </div>
               </div>
               
               <div class="bg-green-50 border border-green-200 rounded-lg p-3">
                 <div class="flex items-center justify-between mb-2">
                   <span class="font-medium text-sm">Afternoon Shift</span>
                   <span class="text-xs text-gray-500">2:00 PM - 10:00 PM</span>
                 </div>
                 <div class="flex items-center gap-2">
                   <div class="w-6 h-6 rounded-full bg-green-400"></div>
                   <span class="text-sm text-gray-700">Mike Chen</span>
                   <span class="ml-auto text-xs bg-green-100 text-green-700 px-2 py-1 rounded">Trainer</span>
                 </div>
               </div>
               
               <div class="bg-purple-50 border border-purple-200 rounded-lg p-3">
                 <div class="flex items-center justify-between mb-2">
                   <span class="font-medium text-sm">Evening Classes</span>
                   <span class="text-xs text-gray-500">6:00 PM - 9:00 PM</span>
                 </div>
                 <div class="flex items-center gap-2">
                   <div class="w-6 h-6 rounded-full bg-purple-400"></div>
                   <span class="text-sm text-gray-700">Jessica Lee</span>
                   <span class="ml-auto text-xs bg-purple-100 text-purple-700 px-2 py-1 rounded">Instructor</span>
                 </div>
               </div>
             </div>
           </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Trusted By -->
  <div class="mt-20 relative w-full max-w-5xl">
    <p class="text-sm text-gray-500 mb-6 text-left ml-4">Trusted by managers at</p>
    <div class="flex flex-wrap justify-between items-center gap-8 opacity-50 grayscale">
       <span class="font-bold text-xl">24 Hour Fitness</span>
       <span class="font-bold text-xl">Equinox</span>
       <span class="font-bold text-xl">LA Fitness</span>
       <span class="font-bold text-xl">Starbucks</span>
       <span class="font-bold text-xl">Blue Bottle</span>
       <span class="font-bold text-xl">Philz Coffee</span>
    </div>
    
    <!-- Handwritten Note -->
    <div class="absolute -bottom-12 -left-4 hidden lg:block">
      <div class="relative">
        <svg class="absolute -top-4 -right-8 w-12 h-12 text-gray-300 transform rotate-12" viewBox="0 0 100 100" fill="none" stroke="currentColor">
           <path d="M10,80 Q50,10 90,80" stroke-width="2" />
           <path d="M90,80 L80,70 M90,80 L85,90" stroke-width="2" />
        </svg>
        <p class="font-serif italic text-gray-400 text-sm whitespace-nowrap transform -rotate-6">
          * Scheduling 50,000+ shifts per month
        </p>
      </div>
    </div>
  </div>
</section>
