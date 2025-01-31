---
title: UNH Insect Database
lead: Advancing Insect Research through Taxonomic Excellence
project: UNH Insect Database
---

<!-- Updated Header Section: Cleaner and More Compact -->
<div style="background-color: var(--color-header-footer-bg); color: var(--color-header-footer-text);" class="py-8 px-6 rounded-b-md mb-8 text-center">
  <h1 class="text-3xl font-bold">{{ frontmatter.title }}</h1>
  <p class="mt-2 text-base">{{ frontmatter.lead }}</p>
</div>

<!-- Updated Boxes Section -->
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 space-y-8">
  <!-- Two-Column Grid -->
  <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
    <!-- Explore Our Collection Card -->
    <div style="background: linear-gradient(135deg, var(--neutral-bg), var(--color-base-muted)); border: 1px solid var(--color-base-border);" class="rounded-xl p-8 shadow-xl transform hover:scale-105 transition duration-300">
      <h2 style="color: var(--color-base-foreground);" class="text-2xl font-bold mb-4">Explore Our Collection</h2>
      <p style="color: var(--color-base-content);" class="mb-6">
        Utilize the search feature below to access detailed taxonomic records from our collection, supporting scholarly research and biodiversity studies. Specimens lacking Data or images are species that the unh coollection does not have.
      </p>  
      <autocomplete-otu class="w-full max-w-lg mx-auto my-4"/>
    </div>

  <!-- Research Highlights Card -->
  <div style="background: linear-gradient(135deg, var(--neutral-bg), var(--color-base-muted)); border: 1px solid var(--color-base-border);" class="rounded-xl p-8 shadow-xl transform hover:scale-105 transition duration-300">
      <h2 style="color: var(--color-base-foreground);" class="text-2xl font-bold mb-4">Research Highlights</h2>
      <p style="color: var(--color-base-content);">
        Stay informed about recent discoveries, notable specimen additions, and ongoing research projects conducted by our entomology team.
      </p>
    </div>
  </div>

  <!-- Important Notice Card -->
  <div style="background: linear-gradient(135deg, var(--neutral-bg), var(--color-base-muted)); border: 1px solid var(--color-base-border);" class="rounded-xl p-8 shadow-xl transform hover:scale-105 transition duration-300">
    <h2 style="color: var(--color-base-foreground);" class="text-2xl font-bold mb-4">Important Notice</h2>
    <p style="color: var(--color-base-content);">
      Our database is continuously updated as new specimens are cataloged and research findings evolve. Data accuracy and completeness are ongoing priorities.
    </p>
  </div>

  <!-- Get Involved Card -->
  <div style="background: linear-gradient(135deg, var(--neutral-bg), var(--color-base-muted)); border: 1px solid var(--color-base-border);" class="rounded-xl p-8 shadow-xl transform hover:scale-105 transition duration-300">
    <h2 style="color: var(--color-base-foreground);" class="text-2xl font-bold mb-4">Get Involved</h2>
    <p style="color: var(--color-base-content);">
      Learn how you can contribute to and collaborate with the <em>{{ frontmatter.project }}</em>. For detailed project descriptions, partnership opportunities, and contact information, visit our 
      <a href="/about" style="color: var(--color-primary-content);" class="hover:underline">About</a> page.
    </p>
  </div>
</div>
