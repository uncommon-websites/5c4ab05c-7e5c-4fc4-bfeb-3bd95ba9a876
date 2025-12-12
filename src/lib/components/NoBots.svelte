<script lang="ts">
  // No Bots Section
</script>

<section class="py-24 bg-gray-50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid md:grid-cols-2 gap-16 items-center">
      <div>
        <h2 class="text-3xl font-bold mb-6">Automatic conflict resolution</h2>
        <p class="text-gray-600 mb-8">
          When you schedule with newRota, AI handles all the complexity. No more manual checking for conflicts or availability issues:
        </p>
        
        <ul class="space-y-4">
          {#each ['Detects scheduling conflicts before they happen', 'Respects time-off requests and availability windows', 'Balances workload fairly across all staff', 'Suggests optimal shift swaps when changes occur'] as item}
            <li class="flex items-start gap-3">
              <div class="w-5 h-5 rounded-full bg-green-100 flex items-center justify-center mt-0.5 shrink-0">
                <svg class="w-3 h-3 text-green-600" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" />
                </svg>
              </div>
              <span class="text-gray-700 text-sm">{item}</span>
            </li>
          {/each}
        </ul>
      </div>
      
      <div class="relative">
        <!-- Schedule Visualization -->
        <div class="bg-gradient-to-br from-[oklch(0.828_0.111_230.318)] to-[oklch(0.901_0.058_230.902)] rounded-2xl p-8 shadow-lg">
           <div class="bg-white rounded-xl overflow-hidden shadow-2xl relative aspect-video flex items-center justify-center p-6">
              <!-- Conflict Resolution Animation -->
              <div class="absolute top-4 left-1/2 -translate-x-1/2 bg-green-600 rounded-full px-4 py-2 flex items-center gap-2 shadow-lg z-10">
                 <svg class="w-4 h-4 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                   <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" />
                 </svg>
                 <span class="text-white text-xs font-medium">3 conflicts resolved automatically</span>
              </div>

              <!-- Schedule Grid -->
              <div class="grid grid-cols-5 gap-3 w-full h-full pt-12">
                 <div class="bg-blue-100 border-2 border-blue-300 rounded-lg p-2 flex flex-col justify-between">
                   <div class="text-[10px] font-bold text-blue-900">MON 6AM</div>
                   <div class="w-6 h-6 rounded-full bg-blue-500 mx-auto"></div>
                 </div>
                 <div class="bg-green-100 border-2 border-green-300 rounded-lg p-2 flex flex-col justify-between">
                   <div class="text-[10px] font-bold text-green-900">TUE 2PM</div>
                   <div class="w-6 h-6 rounded-full bg-green-500 mx-auto"></div>
                 </div>
                 <div class="bg-purple-100 border-2 border-purple-300 rounded-lg p-2 flex flex-col justify-between">
                   <div class="text-[10px] font-bold text-purple-900">WED 10AM</div>
                   <div class="w-6 h-6 rounded-full bg-purple-500 mx-auto"></div>
                 </div>
                 <div class="bg-orange-100 border-2 border-orange-300 rounded-lg p-2 flex flex-col justify-between">
                   <div class="text-[10px] font-bold text-orange-900">THU 6PM</div>
                   <div class="w-6 h-6 rounded-full bg-orange-500 mx-auto"></div>
                 </div>
                 <div class="bg-pink-100 border-2 border-pink-300 rounded-lg p-2 flex flex-col justify-between">
                   <div class="text-[10px] font-bold text-pink-900">FRI 9AM</div>
                   <div class="w-6 h-6 rounded-full bg-pink-500 mx-auto"></div>
                 </div>
              </div>
           </div>
        </div>
        <p class="text-xs text-gray-500 mt-4 text-center">
          AI analyzes hundreds of scheduling combinations to find the optimal solution in seconds.
        </p>
      </div>
    </div>
    
    <div class="mt-16 p-6 bg-green-50 rounded-xl border border-green-100">
      <p class="text-sm text-green-800">
        <span class="font-bold">The automatic conflict detection saved me hours of headaches</span>. I used to spend forever checking if everyone was available. Now newRota does it instantly and even suggests better alternatives when there's an issue.
      </p>
      <div class="mt-2 text-xs text-green-600 font-medium">Jennifer Park • Operations Manager, Peak Fitness</div>
    </div>
  </div>
</section>
