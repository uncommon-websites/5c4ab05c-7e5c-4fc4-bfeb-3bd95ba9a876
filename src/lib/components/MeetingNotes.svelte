<script lang="ts">
  // Meeting Notes Section
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
  <div class="mb-4">
    <span class="text-green-600 font-medium">Smart Scheduling</span>
  </div>
  
  <h2 class="text-4xl font-bold mb-4">AI-powered shift optimization for your team</h2>
  
  <div class="flex gap-4 text-sm text-gray-500 mb-12 items-center">
    <span class="font-medium text-gray-900">Replaces:</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-blue-600"></div> When I Work</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-orange-500"></div> Deputy</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-green-600"></div> Homebase</span>
  </div>

  <div class="grid md:grid-cols-2 gap-16 mb-20">
    <div>
      <h3 class="font-bold text-lg mb-4">Why newRota?</h3>
      <p class="text-gray-600 mb-4 leading-relaxed">
        There are dozens of scheduling tools out there. If basic shift templates are all you need, any of them will work. Many are even cheaper.
      </p>
      <p class="text-gray-600 leading-relaxed">
        But if you want to eliminate scheduling headaches and save real time, you need newRota. Our AI understands your staff's availability and automatically creates optimized schedules that work for everyone.
      </p>
    </div>
    
    <div class="space-y-8">
      <!-- Testimonial 1 -->
      <div class="bg-gray-50 p-6 rounded-2xl relative">
        <div class="flex text-orange-400 mb-2">★★★★★</div>
        <div class="flex items-center gap-3 mb-3">
          <div class="w-8 h-8 bg-gray-300 rounded-full"></div>
          <div>
            <div class="font-bold text-sm">Marcus Rodriguez</div>
            <div class="text-xs text-gray-500">Manager • FitLife Gym</div>
          </div>
        </div>
        <p class="text-sm text-gray-700">
          newRota cut my scheduling time from 4 hours to 15 minutes per week. The AI handles all the availability conflicts automatically, and my staff loves getting their schedules instantly.
        </p>
        <div class="absolute top-4 right-4 w-6 h-6 bg-[oklch(0.588_0.158_241.966)] rounded-md"></div>
      </div>

       <!-- Testimonial 2 -->
       <div class="bg-gray-50 p-6 rounded-2xl relative">
        <div class="flex text-orange-400 mb-2">★★★★★</div>
        <div class="flex items-center gap-3 mb-3">
          <div class="w-8 h-8 bg-gray-300 rounded-full"></div>
          <div>
            <div class="font-bold text-sm">Sarah Chen</div>
            <div class="text-xs text-gray-500">Owner • Brew & Bean Coffee</div>
          </div>
        </div>
        <p class="text-sm text-gray-700">
          Managing three coffee shop locations was a nightmare until newRota. Now I can see all my schedules in one place and the AI makes sure every shift is covered. Game changer for my business.
        </p>
        <div class="absolute top-4 right-4 w-6 h-6 bg-green-600 rounded-md"></div>
      </div>
    </div>
  </div>

  <div class="max-w-3xl mb-12">
    <h3 class="font-bold text-lg mb-4">Availability Matching & Conflict Resolution</h3>
    <p class="text-gray-600 mb-4 leading-relaxed">
      Manual scheduling means constant back-and-forth with your team. Staff request time off, availability changes, and you're stuck playing schedule Tetris. But every schedule should work smoothly for everyone. Basic scheduling tools create conflicts because they don't understand your team's needs. Ours does, and creates schedules that actually work.
    </p>
    <p class="text-gray-600 leading-relaxed">
      The problem with traditional scheduling is it doesn't account for real-world constraints. We solve this with intelligent AI that learns your patterns.
    </p>
  </div>

  <!-- Large Interface Image -->
  <div class="w-full bg-gray-900 rounded-2xl overflow-hidden shadow-2xl border border-gray-800 pt-2 md:pt-8 px-2 md:px-8 pb-0">
    <!-- Feature Tabs (Dark Header) -->
    <div class="flex justify-center gap-8 mb-6 text-sm font-medium text-gray-400">
      <div class="flex items-center gap-2 hover:text-white cursor-pointer transition-colors">
        <div class="w-4 h-4 rounded-full border border-gray-600"></div>
        Auto-fill shifts
      </div>
      <div class="flex items-center gap-2 text-white cursor-pointer">
        <div class="w-4 h-4 rounded-full bg-white text-gray-900 flex items-center justify-center text-[10px]">✨</div>
        AI Optimization
      </div>
      <div class="flex items-center gap-2 hover:text-white cursor-pointer transition-colors">
        <div class="w-4 h-4 rounded-full border border-gray-600"></div>
        Conflict detection
      </div>
    </div>

    <!-- App Window -->
    <div class="bg-white rounded-t-lg overflow-hidden h-[500px] flex flex-col shadow-2xl relative">
       <!-- Header -->
       <div class="border-b border-gray-100 p-4 flex justify-between items-center bg-white z-10">
         <div class="flex items-center gap-3">
           <div class="w-8 h-8 bg-[oklch(0.828_0.111_230.318)] rounded-lg flex items-center justify-center text-[oklch(0.588_0.158_241.966)]">📋</div>
           <div class="font-bold text-gray-900">Weekly Schedule</div>
         </div>
         <div class="flex items-center gap-3">
           <div class="flex -space-x-2">
             <div class="w-6 h-6 rounded-full bg-blue-400 border-2 border-white"></div>
             <div class="w-6 h-6 rounded-full bg-green-400 border-2 border-white"></div>
             <div class="w-6 h-6 rounded-full bg-purple-400 border-2 border-white"></div>
             <div class="w-6 h-6 rounded-full bg-orange-400 border-2 border-white flex items-center justify-center text-white text-[10px] font-bold">+8</div>
           </div>
           <div class="h-4 w-px bg-gray-200"></div>
           <button class="text-xs font-medium text-gray-500">Export</button>
           <button class="bg-[oklch(0.588_0.158_241.966)] text-white px-3 py-1.5 rounded-md text-xs font-medium">Publish</button>
         </div>
       </div>

       <!-- Content Area -->
       <div class="flex-1 overflow-y-auto bg-white p-6 md:p-8">
         <!-- Metadata -->
         <div class="grid grid-cols-[100px_1fr] gap-y-4 text-sm mb-8">
           <div class="text-gray-500">Location</div>
           <div class="text-gray-900 font-medium">Downtown Gym</div>
           
           <div class="text-gray-500">Week</div>
           <div class="flex items-center gap-2">
             <div class="w-1 h-4 bg-[oklch(0.588_0.158_241.966)] rounded-full"></div>
             <span class="font-medium">Jan 15-21, 2024</span>
           </div>
           
           <div class="text-gray-500">Coverage</div>
           <div class="flex items-center gap-2">
             <div class="h-2 w-32 bg-gray-100 rounded-full overflow-hidden">
               <div class="h-full w-[92%] bg-green-500"></div>
             </div>
             <span class="text-xs text-gray-900 font-medium">92% filled</span>
           </div>
         </div>
         
         <!-- Tabs -->
         <div class="flex gap-6 border-b border-gray-100 mb-6">
           <button class="pb-2 border-b-2 border-black font-medium text-sm">Schedule</button>
           <button class="pb-2 border-b-2 border-transparent text-gray-500 font-medium text-sm hover:text-gray-800">Staff</button>
           <button class="pb-2 border-b-2 border-transparent text-gray-500 font-medium text-sm hover:text-gray-800">Availability</button>
         </div>
         
         <!-- Schedule Content -->
         <div class="space-y-6 max-w-2xl">
            <div>
              <div class="flex items-center gap-2 mb-3">
                <span class="text-xs font-bold uppercase tracking-wider text-gray-400">AI Optimization Results</span>
                <span class="text-xs bg-green-100 text-green-700 px-2 py-0.5 rounded-full">3 conflicts resolved</span>
              </div>
              <h4 class="font-bold text-gray-900 mb-2">Shift Assignments</h4>
              <ul class="list-disc pl-5 text-sm text-gray-600 space-y-2 marker:text-gray-300">
                <li>Morning shifts (6 AM - 2 PM) optimally distributed across 12 staff members based on availability preferences</li>
                <li>Peak hours (5 PM - 8 PM) fully staffed with certified trainers and front desk coverage</li>
                <li>Weekend coverage balanced to ensure fair rotation among all team members</li>
              </ul>
            </div>
            
             <div>
              <h4 class="font-bold text-gray-900 mb-2">Coverage Analysis</h4>
              <ul class="list-disc pl-5 text-sm text-gray-600 space-y-2 marker:text-gray-300">
                <li>All front desk shifts covered with backup staff identified</li>
                <li>Personal training sessions matched to trainer certifications and client preferences</li>
                <li>2 open shifts remaining: Thursday 2-6 PM, Saturday 10 AM - 2 PM</li>
              </ul>
            </div>
         </div>
       </div>
    </div>
  </div>

  <!-- Industry Types -->
  <div class="mt-12 text-center">
    <div class="flex flex-wrap justify-center gap-8 text-2xl font-bold text-gray-300 mb-4 select-none">
      <span>🏋️ Gyms</span>
      <span>☕ Coffee Shops</span>
      <span>🍽️ Restaurants</span>
      <span>🏪 Retail</span>
      <span>🏥 Healthcare</span>
      <span>🏨 Hospitality</span>
    </div>
    <p class="text-xs text-gray-400">
      Pre-built shift templates for <span class="underline decoration-dotted">6 industries</span>. Custom templates available for any business.
    </p>
  </div>
</section>
