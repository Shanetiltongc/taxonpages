---
title: UNH Insect Database
lead: Advancing Insect Research through Taxonomic Excellence
project: UNH Insect Database
---

<!-- HERO SECTION -->
<div class="homepage-header py-10 px-8 rounded-b-lg mb-8 shadow-lg">
  <div class="max-w-4xl mx-auto text-center">
    <h1 class="text-4xl font-extrabold tracking-wide animate-fade-in">{{ frontmatter.title }}</h1>
    <p class="mt-3 text-lg italic opacity-90">{{ frontmatter.lead }}</p>
  </div>
</div>

<style>
@keyframes fade-in {
  from { opacity: 0; transform: translateY(-10px); }
  to { opacity: 1; transform: translateY(0); }
}
.animate-fade-in { animation: fade-in 0.8s ease-out; }

/* Header Styling */
.homepage-header {
  background: linear-gradient(to bottom, var(--color-header-footer-bg), rgba(1, 61, 122, 0.1));
  color: var(--color-header-footer-text);
}
.dark .homepage-header {
  background: linear-gradient(to bottom, var(--color-header-footer-bg), rgba(22, 33, 54, 0.2));
}

/* Image Styling */
.image-card img {
  width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: var(--shadow-md);
}

/* Two-Column Layout */
.grid-two-columns {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.5rem;
  align-items: start;
}

/* Card Styling */
.card {
  background: linear-gradient(135deg, var(--neutral-bg), var(--color-base-muted));
  border: 1px solid var(--color-base-border);
  border-radius: 12px;
  padding: 1rem 1.5rem;
  box-shadow: var(--shadow-md);
  display: flex;
  flex-direction: column;
  justify-content: center;
  min-height: auto;
}
</style>

<!-- MAIN CONTENT -->
## Welcome to the UNH Insect Database
Explore thousands of specimens cataloged for research, education, and biodiversity conservation.

---

<!-- TWO-COLUMN GRID -->
<div class="grid-two-columns">
  
  <!-- Left: Image -->
  <div class="image-card">
    <img src="/src/assets/images/Insects/NCSU_0025626_Head_View_3X.jpg" alt="Pinned Bee Specimen">
  </div>

  <!-- Right: Text -->
  <div class="card">
    <h2 class="text-xl font-bold mb-2">A Legacy of Discovery</h2>
    <p>UNH's entomology collection preserves rare and significant insect specimens, aiding research across multiple disciplines.</p>
  </div>

</div>

---

<!-- DATABASE & INSTAGRAM ROW -->
<div class="grid-two-columns">

  <!-- Explore Our Collection -->
  <div class="card">
    <h2 class="text-xl font-bold mb-2">Search Our Database</h2>
    <p>Use our advanced search tool to access taxonomic records, supporting biodiversity studies.</p>
    <autocomplete-otu class="w-full max-w-lg mx-auto my-4"/>
  </div>

  <!-- Instagram -->
  <div class="card">
    <h2 class="text-xl font-bold mb-2">Follow Us on Instagram</h2>
    <p>See behind-the-scenes content and student discoveries at the UNH Entomology Lab.</p>  
    <a href="https://www.instagram.com/unhentomologycollection" target="_blank"
       style="display: inline-block; background-color: var(--color-primary); color: var(--color-primary-content); padding: 0.5rem 1rem; border-radius: 4px; text-decoration: none; font-weight: bold;">
      Visit Instagram
    </a>
  </div>

</div>

---

<!-- GRID LAYOUT FOR FEATURED INSECTS -->
## Featured Insect Photography
<div class="grid-two-columns">

  <!-- Image 1 -->
  <div class="image-card">
    <img src="/src/assets/images/Insects/Owen1.jpg" alt="Butterfly in Grass">
  </div>

  <!-- Image 2 -->
  <div class="image-card">
    <img src="/src/assets/images/Insects/Owen2.jpg" alt="Parasitic Wasp with Caterpillar">
  </div>

  <!-- Image 3 -->
  <div class="image-card">
    <img src="/src/assets/images/Insects/Owen3.jpg" alt="Metallic Green Tiger Beetle">
  </div>

  <!-- Image 4 -->
  <div class="image-card">
    <img src="/src/assets/images/Insects/Owen4.jpg" alt="Ant on Tree Branch">
  </div>

</div>

---

<!-- GET INVOLVED SECTION -->
## Get Involved
<div class="card">
  <h2 class="text-xl font-bold mb-2">Contribute to Our Research</h2>
  <p>Want to participate in entomology research? Learn how you can get involved with the <em>{{ frontmatter.project }}</em>.</p>
  <a href="/about" class="text-blue-500 hover:underline">Learn More</a>
</div>
