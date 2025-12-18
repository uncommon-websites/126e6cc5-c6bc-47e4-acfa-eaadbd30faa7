<script lang="ts">
  const steps = [
    {
      num: "01",
      title: "Choose your package",
      desc: "Select from our three party packages or create a custom experience for your group event.",
      img: "/generated/image-birthday-party-setup-in-activity-center--1766036163974-11.webp"
    },
    {
      num: "02",
      title: "Book online",
      desc: "Pick your date and time through our easy online booking system. We'll confirm within 24 hours.",
      img: "/generated/image-family-with-kids-entering-a-modern-enter-1766036161128-10.webp"
    },
    {
      num: "03",
      title: "Show up & jump",
      desc: "We handle everything—decorations, food, drinks, and cleanup. You just bring the birthday kid!",
      img: "/generated/image-children-having-fun-at-a-birthday-party--1766036134475-1.webp"
    },
    {
      num: "04",
      title: "Make memories",
      desc: "Your dedicated party host ensures everyone has a blast. Leave with happy, tired kids and amazing photos.",
      img: "/generated/image-group-of-diverse-kids-ages-5-13-jumping--1766036149376-6.webp"
    }
  ];
</script>

<section class="bg-white py-24 px-6">
  <div class="max-w-[1200px] mx-auto">
    <h2 class="text-[40px] leading-tight font-light text-gray-900 mb-16 max-w-[600px]">
      Book the perfect party in four simple steps. Zero stress guaranteed.
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
      {#each steps as step}
        <div class="flex flex-col">
          <div class="bg-black text-white text-xs font-bold w-8 h-8 flex items-center justify-center rounded mb-6">
            {step.num}
          </div>
          <h3 class="text-xl font-normal mb-2">{step.title}</h3>
          <p class="text-gray-500 text-sm leading-relaxed mb-6 min-h-[80px]">{step.desc}</p>
          <div class="rounded-xl overflow-hidden h-[200px] bg-gray-100">
            <img src={step.img} alt={step.title} class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500" />
          </div>
        </div>
      {/each}
    </div>

    <div class="bg-[#f9f9f7] rounded-2xl p-12 flex flex-col md:flex-row items-center justify-between gap-8">
      <div>
        <h3 class="text-2xl font-light mb-2">Ready to book?</h3>
        <p class="text-gray-500 text-sm">Check out our party packages and group event options.</p>
      </div>
      <div class="flex gap-4">
        <button class="px-6 py-3 bg-white border border-gray-200 hover:bg-gray-50 rounded-lg text-sm font-medium transition-colors">
          View packages
        </button>
        <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
          Book now
        </button>
      </div>
    </div>
  </div>
</section>
