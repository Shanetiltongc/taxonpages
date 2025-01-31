---
title: UNH Insect Database
lead: Advancing Insect Research through Taxonomic Excellence
project: UNH Insect Database
---

<!-- Updated Hero Section with SVG Wave -->
<div class="relative overflow-hidden mb-12">
  <div class="py-12 px-6 text-center" style="background-color: var(--color-header-footer-bg); color: var(--color-header-footer-text);">
    <h1 class="text-4xl font-extrabold">{{ frontmatter.title }}</h1>
    <p class="mt-4 text-lg">{{ frontmatter.lead }}</p>
  </div>
  <!-- SVG Wave Shape -->
  <svg class="absolute bottom-0 left-0 w-full" viewBox="0 0 1440 320" preserveAspectRatio="none">
    <path fill="var(--color-header-footer-bg)" fill-opacity="1" d="M0,256L60,229.3C120,203,240,149,360,117.3C480,85,600,75,720,85.3C840,96,960,128,1080,144C1200,160,1320,160,1380,160L1440,160L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"></path>
  </svg>
</div>

<!-- Rest of Your Content -->
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
  <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
    <div style="background-color: var(--neutral-bg); border: 1px solid var(--color-base-border);" class="rounded-lg p-8 shadow-lg hover:shadow-2xl transition duration-300 transform hover:-translate-y-1">
      <h2 style="color: var(--color-base-foreground);" class="text-2xl font-bold mb-4">Explore Our Collection</h2>
      <p style="color: var(--color-base-content);" class="mb-6">
        Utilize the search feature below to access detailed taxonomic records from our collection, supporting scholarly research and biodiversity studies.
      </p>  
      <autocomplete-otu class="w-full max-w-lg mx-auto my-4"/>
    </div>

  <div style="background-color: var(--neutral-bg); border: 1px solid var(--color-base-border);" class="rounded-lg p-8 shadow-lg hover:shadow-2xl transition duration-300 transform hover:-translate-y-1">
      <h2 style="color: var(--color-base-foreground);" class="text-2xl font-bold mb-4">Research Highlights</h2>
      <p style="color: var(--color-base-content);">
        Stay informed about recent discoveries, notable specimen additions, and ongoing research projects conducted by our entomology team.
      </p>
    </div>
  </div>

  <div style="background-color: var(--neutral-bg); border: 1px solid var(--color-base-border);" class="rounded-lg p-8 my-8 shadow-lg hover:shadow-2xl transition duration-300 transform hover:-translate-y-1">
    <h2 style="color: var(--color-base-foreground);" class="text-2xl font-bold mb-4">Important Notice</h2>
    <p style="color: var(--color-base-content);">
      Our database is continuously updated as new specimens are cataloged and research findings evolve. Data accuracy and completeness are ongoing priorities.
    </p>
  </div>

  <div style="background-color: var(--neutral-bg); border: 1px solid var(--color-base-border);" class="rounded-lg p-8 my-8 shadow-lg hover:shadow-2xl transition duration-300 transform hover:-translate-y-1">
    <h2 style="color: var(--color-base-foreground);" class="text-2xl font-bold mb-4">Get Involved</h2>
    <p style="color: var(--color-base-content);">
      Learn how you can contribute to and collaborate with the <em>{{ frontmatter.project }}</em>. For detailed project descriptions, partnership opportunities, and contact information, visit our 
      <a href="/about" style="color: var(--color-primary-content);" class="hover:underline">About</a> page.
    </p>
  </div>
</div>
