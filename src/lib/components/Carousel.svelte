<script lang="ts">
  const images = [
    "/generated/image-kids-navigating-through-a-laser-maze-obs-1766036137310-2.webp",
    "/generated/image-children-playing-dodgeball-on-trampoline-1766036140294-3.webp",
    "/generated/image-kids-doing-flips-and-tricks-on-gymnastic-1766036143241-4.webp",
    "/generated/image-kids-climbing-and-swinging-on-aerial-sil-1766036155187-8.webp",
    "/generated/image-children-shooting-basketballs-while-jump-1766036158284-9.webp"
  ];
</script>

<section class="bg-white pb-24 overflow-hidden" id="attractions">
  <div class="flex gap-4 overflow-x-auto px-6 pb-8 snap-x">
    {#each images as img}
      <div class="min-w-[80vw] md:min-w-[60vw] lg:min-w-[45vw] h-[400px] snap-center first:pl-0">
        <img src={img} alt="Park attraction" class="w-full h-full object-cover rounded-lg" />
      </div>
    {/each}
  </div>
  
  <div class="text-center mt-4">
    <p class="text-gray-500 text-sm mb-4">20+ attractions <span class="text-gray-400">All ages welcome</span></p>
    <div class="flex justify-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-gray-800"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
    </div>
  </div>
</section>
