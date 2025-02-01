---
title: UNH Insect Database
lead: Advancing Insect Research through Taxonomic Excellence
project: UNH Insect Database
---

<div class="relative bg-gradient-to-b from-[var(--color-header-footer-bg)] to-[var(--color-base-muted)] text-[var(--color-header-footer-text)] py-10 px-8 rounded-b-lg mb-8 shadow-lg">
  <div class="max-w-4xl mx-auto text-center">
    <h1 class="text-4xl font-extrabold tracking-wide animate-fade-in">{{ frontmatter.title }}</h1>
    <p class="mt-3 text-lg italic opacity-90">{{ frontmatter.lead }}</p>
  </div>
</div>

<style>
@keyframes fade-in {
  from {
    opacity: 0;
    transform: translateY(-10px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.animate-fade-in {
  animation: fade-in 0.8s ease-out;
}
</style>


<!-- Updated Boxes Section -->
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 space-y-8">
  <!-- Two-Column Grid -->
  <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
    <!-- Explore Our Collection Card -->
    <div style="background: linear-gradient(135deg, var(--neutral-bg), var(--color-base-muted)); border: 1px solid var(--color-base-border);" 
         class="rounded-xl p-8 shadow-xl transform hover:scale-105 transition duration-300">
      <h2 style="color: var(--color-base-foreground);" class="text-2xl font-bold mb-4">Explore Our Collection</h2>
      <p style="color: var(--color-base-content);" class="mb-6">
        Utilize the search feature below to access detailed taxonomic records from our collection, supporting scholarly research and biodiversity studies. Specimens lacking data or images are species that the UNH collection does not have.
      </p>  
      <autocomplete-otu class="w-full max-w-lg mx-auto my-4"/>
    </div>

  <!-- Instagram Link Card -->
  <div style="background: linear-gradient(135deg, var(--neutral-bg), var(--color-base-muted)); border: 1px solid var(--color-base-border);" 
         class="rounded-xl p-8 shadow-xl transform hover:scale-105 transition duration-300">
      <h2 style="color: var(--color-base-foreground);" class="text-2xl font-bold mb-4">Follow Us on Instagram</h2>
      <p style="color: var(--color-base-content);" class="mb-6">
        Stay up-to-date with our latest posts, behind-the-scenes looks, and community highlights from our student-run UNH Entomology Lab.
      </p>  
      <a href="https://www.instagram.com/unhentomologycollection?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" target="_blank" style="display: inline-block; background-color: var(--color-primary); color: var(--color-primary-content); padding: 0.5rem 1rem; border-radius: 4px; text-decoration: none; font-weight: bold;">
        Visit Instagram
      </a>
    </div>
  </div>

  <!-- Important Notice Card -->
  <div style="background: linear-gradient(135deg, var(--neutral-bg), var(--color-base-muted)); border: 1px solid var(--color-base-border);" 
       class="rounded-xl p-8 shadow-xl transform hover:scale-105 transition duration-300">
    <h2 style="color: var(--color-base-foreground);" class="text-2xl font-bold mb-4">Important Notice</h2>
    <p style="color: var(--color-base-content);">
      Our database is continuously updated as new specimens are cataloged and research findings evolve. Data accuracy and completeness are ongoing priorities.
    </p>
  </div>

  <!-- Get Involved Card -->
  <div style="background: linear-gradient(135deg, var(--neutral-bg), var(--color-base-muted)); border: 1px solid var(--color-base-border);" 
       class="rounded-xl p-8 shadow-xl transform hover:scale-105 transition duration-300">
    <h2 style="color: var(--color-base-foreground);" class="text-2xl font-bold mb-4">Get Involved</h2>
    <p style="color: var(--color-base-content);">
      Learn how you can contribute to and collaborate with the <em>{{ frontmatter.project }}</em>. For detailed project descriptions, partnership opportunities, and contact information, visit our 
      <a href="/about" style="color: var(--color-primary-content);" class="hover:underline">About</a> page.
    </p>
  </div>
</div>
