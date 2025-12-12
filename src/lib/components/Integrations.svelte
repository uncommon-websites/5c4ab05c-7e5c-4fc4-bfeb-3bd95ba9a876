<script lang="ts">
  // Integrations Section
</script>

<section class="py-24 bg-white">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
    <div class="mb-4">
      <span class="text-blue-500 font-medium">Integrations</span>
    </div>
    
    <h2 class="text-4xl font-bold mb-6">Sync with your existing tools</h2>
    
    <p class="text-gray-600 max-w-3xl mx-auto mb-16">
      newRota integrates with the tools you already use. Connect your payroll system to automatically sync hours worked. Link your POS system to match schedules with sales forecasts.
      <br><br>
      Export schedules to your team communication tools like Slack or Microsoft Teams. Sync with Google Calendar so everyone sees their shifts.
      <br><br>
      We know you have existing systems. That's why we've built integrations with major payroll providers, POS systems, and communication platforms. Your schedules flow seamlessly into your workflow.
    </p>
    
    <!-- Integration Diagram Mockup -->
    <div class="relative max-w-4xl mx-auto h-[400px] mb-16 flex items-center justify-center">
      <!-- Center Hub -->
      <div class="w-32 h-32 bg-gradient-to-br from-[oklch(0.588_0.158_241.966)] to-[oklch(0.746_0.16_232.661)] rounded-3xl shadow-2xl z-10 flex items-center justify-center">
        <div class="text-white font-bold text-3xl">nR</div>
      </div>
      <div class="absolute bottom-28 text-gray-400 font-serif italic text-xl">via newRota</div>
      
      <!-- Connections (Simplified with CSS) -->
      <div class="absolute inset-0 flex items-center justify-center">
         <!-- Left Side Icons -->
         <div class="absolute left-10 top-10 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-green-600 font-bold text-xl border border-gray-100">G</div>
         <div class="absolute left-10 bottom-10 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-blue-500 font-bold text-xl border border-gray-100">Q</div>
         <div class="absolute left-0 top-1/2 -translate-y-1/2 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-orange-500 font-bold text-xl border border-gray-100">S</div>
         
         <!-- Right Side Icons -->
         <div class="absolute right-10 top-10 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-purple-600 font-bold text-xl border border-gray-100">S</div>
         <div class="absolute right-10 bottom-10 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-blue-600 font-bold text-xl border border-gray-100">T</div>
         <div class="absolute right-0 top-1/2 -translate-y-1/2 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-red-500 font-bold text-xl border border-gray-100">T</div>
         
         <!-- Connecting Lines (SVG) -->
         <svg class="absolute inset-0 w-full h-full pointer-events-none -z-10 text-gray-200" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M350,200 C300,200 100,100 80,60" />
            <path d="M350,200 C300,200 100,300 80,340" />
            <path d="M350,200 C300,200 80,200 60,200" />
            
            <path d="M550,200 C600,200 800,100 820,60" />
            <path d="M550,200 C600,200 800,300 820,340" />
            <path d="M550,200 C600,200 820,200 840,200" />
         </svg>
      </div>
    </div>
    
    <p class="text-xs text-gray-400 mb-16">Export schedules to Slack, QuickBooks, Square, Toast, Gusto. Request integrations at support@newrota.com</p>
    
    <!-- Integration List Grid -->
    <div class="grid grid-cols-2 md:grid-cols-3 gap-8 text-left max-w-4xl mx-auto">
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-green-600 rounded flex items-center justify-center text-white font-bold text-xs">G</div>
        <div>
          <div class="font-bold text-sm">Gusto</div>
          <div class="text-xs text-gray-500">Sync payroll hours</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-blue-500 rounded flex items-center justify-center text-white font-bold text-xs">Q</div>
        <div>
          <div class="font-bold text-sm">QuickBooks</div>
          <div class="text-xs text-gray-500">Export timesheets</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-purple-600 rounded flex items-center justify-center text-white font-bold text-xs">S</div>
        <div>
          <div class="font-bold text-sm">Slack</div>
          <div class="text-xs text-gray-500">Send schedule updates</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-orange-500 rounded flex items-center justify-center text-white font-bold text-xs">S</div>
        <div>
          <div class="font-bold text-sm">Square</div>
          <div class="text-xs text-gray-500">Match POS data</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-red-500 rounded flex items-center justify-center text-white font-bold text-xs">T</div>
        <div>
          <div class="font-bold text-sm">Toast</div>
          <div class="text-xs text-gray-500">Restaurant POS sync</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-blue-600 rounded flex items-center justify-center text-white font-bold text-xs">T</div>
        <div>
          <div class="font-bold text-sm">Microsoft Teams</div>
          <div class="text-xs text-gray-500">Team notifications</div>
        </div>
      </div>
      <div class="flex items-start gap-3 opacity-50">
        <div class="w-8 h-8 bg-gray-400 rounded flex items-center justify-center text-white font-bold text-xs">A</div>
        <div>
          <div class="font-bold text-sm">ADP <span class="font-normal text-gray-400">Soon</span></div>
          <div class="text-xs text-gray-500">Payroll integration</div>
        </div>
      </div>
       <div class="flex items-start gap-3 opacity-50">
        <div class="w-8 h-8 bg-purple-400 rounded flex items-center justify-center text-white font-bold text-xs">Z</div>
        <div>
          <div class="font-bold text-sm">Zenefits <span class="font-normal text-gray-400">Soon</span></div>
          <div class="text-xs text-gray-500">HR platform sync</div>
        </div>
      </div>
       <div class="flex items-start gap-3 opacity-50">
        <div class="w-8 h-8 bg-green-400 rounded flex items-center justify-center text-white font-bold text-xs">C</div>
        <div>
          <div class="font-bold text-sm">Clover <span class="font-normal text-gray-400">Soon</span></div>
          <div class="text-xs text-gray-500">POS integration</div>
        </div>
      </div>
    </div>
  </div>
</section>
