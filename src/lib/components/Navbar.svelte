<script lang="ts">
  import { page } from '$app/stores';
</script>

<nav class="bg-black text-white py-4 px-6 flex items-center justify-between sticky top-0 z-50 border-b border-gray-900">
  <div class="flex items-center gap-8">
    <a href="/" class="flex items-center gap-2">
      <svg width="32" height="38" viewBox="0 0 111 132" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M55.363 13.7842V65.7772L43.5135 59.006C22.4745 46.9146 9.41574 24.4246 9.41574 0H0.709961V59.4896C0.709961 78.8359 11.834 96.7311 29.4875 105.195L55.6049 117.77V65.7772L67.4544 72.5483C88.4934 84.6397 101.552 107.13 101.552 131.554H110.258V72.0646C110.258 52.7184 99.1339 34.8232 81.4804 26.3592L55.363 13.7842Z" fill="white"/>
      </svg>
      <span class="text-xl font-bold tracking-tight">Ninja Kidz Action Park</span>
    </a>
    
    <div class="hidden md:flex items-center gap-6 text-[13px] font-medium text-gray-300">
      <a href="#attractions" class="hover:text-white transition-colors">Attractions</a>
      <a href="#parties" class="hover:text-white transition-colors">Birthday Parties</a>
      <a href="#locations" class="hover:text-white transition-colors">Locations</a>
      <a href="#groups" class="hover:text-white transition-colors">Group Events</a>
      <a href="#memberships" class="hover:text-white transition-colors">Memberships</a>
    </div>
  </div>

  <div class="flex items-center gap-4">
    <button class="text-gray-300 hover:text-white transition-colors">
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.3-4.3"/></svg>
    </button>
    <a href="#" class="bg-primary-600 hover:bg-primary-700 text-white px-4 py-2 rounded-full text-[13px] font-medium transition-colors">
      Book a party
    </a>
  </div>
</nav>
