<script lang="ts">
  // AI Chat Section
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
  <div class="mb-4">
    <span class="text-blue-500 font-medium">AI Assistant</span>
  </div>
  
  <h2 class="text-4xl font-bold mb-12">Ask newRota to schedule anything</h2>
  
  <div class="grid lg:grid-cols-2 gap-16 mb-24">
    <div>
      <div class="flex gap-4 mb-8">
        <div class="text-6xl text-gray-200 font-serif leading-none">“</div>
        <div>
          <p class="text-lg font-medium text-gray-900 mb-2">
            It's like having a scheduling expert on staff. The AI understands my team's preferences, handles time-off requests, and creates schedules that actually work. No more spreadsheets.
          </p>
          <div class="text-sm text-gray-500">Alex Thompson • Owner, CrossFit Downtown</div>
        </div>
      </div>
      
      <div class="relative mt-12 bg-gray-50 p-6 rounded-xl border border-gray-100">
        <div class="absolute -top-8 left-0 text-green-500 font-handwriting transform -rotate-6 text-sm flex items-center gap-1">
          From a happy customer 
          <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor"><path d="M10 10l5 5m0 0l-5 5m5-5H3" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
        </div>
        
        <!-- Email Mockup -->
        <div class="bg-white shadow-sm rounded border border-gray-200 p-4 text-sm">
           <div class="border-b border-gray-100 pb-2 mb-2">
             <div class="flex gap-2 mb-1"><span class="text-gray-500 w-12">From</span> <span class="font-medium">Rachel Kim</span></div>
             <div class="flex gap-2"><span class="text-gray-500 w-12">Subject</span> <span class="font-medium">newRota is a game-changer!</span></div>
           </div>
           <div class="space-y-3 text-gray-700">
             <p>Just wanted to say newRota has completely transformed how I run my coffee shops. I went from spending 5+ hours per week on schedules to maybe 30 minutes.</p>
             <p>The AI handles all the complexity - availability, time-off, certifications, even employee preferences. My staff is happier because they get schedules that work for them.</p>
             <p class="font-bold">Here's what I love most:</p>
             <p>1. Auto-fill shifts based on availability → AI optimizes for fairness → publish instantly<br>
             2. Staff requests time off → AI automatically adjusts schedule → no conflicts ever</p>
           </div>
        </div>
        <div class="text-center mt-4 text-xs text-gray-400">We love hearing success stories like Rachel's.</div>
      </div>
    </div>
    
    <!-- Smart Commands -->
    <div>
      <h3 class="font-bold text-lg mb-4">Smart Commands</h3>
      <p class="text-gray-600 mb-8 text-sm">
        Saving you time is our priority. Smart commands make scheduling effortless. You can ask newRota to fill open shifts, swap staff between locations, adjust for time-off requests, and more.
      </p>
      
      <div class="bg-[oklch(0.828_0.111_230.318)] p-3 rounded-lg inline-block mb-8 text-sm text-[oklch(0.5_0.134_242.749)]">
        <span class="font-bold">One of my favorite use cases:</span> "Sarah needs Friday off, find someone to cover her shifts." and newRota handles it instantly.
      </div>
    </div>
  </div>
  
  <!-- Large Interface Image for Smart Commands -->
  <div class="bg-gradient-to-b from-gray-800 to-gray-900 rounded-2xl p-2 md:p-8 shadow-2xl overflow-hidden">
    <div class="flex justify-between text-white/70 text-sm mb-4 px-4">
       <div class="flex items-center gap-2"><div class="w-4 h-4 bg-green-400 rounded-full"></div> Auto-fill open shifts</div>
       <div class="flex items-center gap-2"><div class="w-4 h-4 bg-purple-400 rounded-full"></div> Handle time-off requests</div>
       <div class="flex items-center gap-2"><div class="w-4 h-4 bg-blue-400 rounded-full"></div> Optimize coverage</div>
    </div>
    
    <div class="bg-white rounded-t-xl overflow-hidden h-[500px] relative">
       <!-- Mock UI -->
       <div class="p-6">
         <div class="max-w-2xl mx-auto bg-white shadow-xl rounded-xl border border-gray-200 overflow-hidden">
           <div class="bg-gray-50 p-3 border-b border-gray-200 font-medium text-sm text-gray-700">
             Sarah needs Friday off, find someone to cover her morning shift
           </div>
           <div class="p-6 space-y-4">
             <div class="flex gap-3">
               <div class="w-8 h-8 bg-[oklch(0.588_0.158_241.966)] rounded-full shrink-0 flex items-center justify-center text-white text-xs font-bold">nR</div>
               <div class="bg-gray-100 rounded-2xl rounded-tl-none p-3 text-sm text-gray-700 max-w-[80%]">
                 I found 3 staff members available to cover Sarah's Friday morning shift (6 AM - 2 PM). Here are the best matches:
               </div>
             </div>
             
             <!-- Staff Suggestions Card -->
             <div class="border border-gray-200 rounded-lg p-4 ml-11 space-y-3">
               <div class="flex items-center gap-3 pb-3 border-b border-gray-100">
                 <div class="w-8 h-8 rounded-full bg-green-400"></div>
                 <div class="flex-1">
                   <div class="font-medium text-sm">Mike Chen</div>
                   <div class="text-xs text-gray-500">Available • Certified Trainer • Prefers mornings</div>
                 </div>
                 <button class="text-xs bg-[oklch(0.588_0.158_241.966)] text-white px-3 py-1 rounded">Assign</button>
               </div>
               <div class="flex items-center gap-3 pb-3 border-b border-gray-100">
                 <div class="w-8 h-8 rounded-full bg-blue-400"></div>
                 <div class="flex-1">
                   <div class="font-medium text-sm">Emma Rodriguez</div>
                   <div class="text-xs text-gray-500">Available • Front Desk • 2 shifts this week</div>
                 </div>
                 <button class="text-xs bg-gray-200 text-gray-700 px-3 py-1 rounded">Assign</button>
               </div>
               <div class="flex items-center gap-3">
                 <div class="w-8 h-8 rounded-full bg-purple-400"></div>
                 <div class="flex-1">
                   <div class="font-medium text-sm">James Park</div>
                   <div class="text-xs text-gray-500">Available • Certified • 4 shifts this week</div>
                 </div>
                 <button class="text-xs bg-gray-200 text-gray-700 px-3 py-1 rounded">Assign</button>
               </div>
             </div>
             
             <div class="flex gap-3">
               <div class="w-8 h-8 bg-[oklch(0.588_0.158_241.966)] rounded-full shrink-0 flex items-center justify-center text-white text-xs font-bold">nR</div>
               <div class="bg-gray-100 rounded-2xl rounded-tl-none p-3 text-sm text-gray-700 max-w-[80%]">
                 I recommend Mike Chen - he has the right certification, prefers morning shifts, and this would balance his workload for the week.
               </div>
             </div>
           </div>
         </div>
       </div>
    </div>
  </div>
</section>
