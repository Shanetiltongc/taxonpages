---
title: UNH Insect Database
lead: Advancing Insect Research through Taxonomic Excellence
project: UNH Insect Database
---

<div class="relative homepage-header py-10 px-8 rounded-b-lg mb-8 shadow-lg">
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

/* Image Grid */
.image-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
  margin: 2rem auto;
  max-width: 1000px;
  padding: 1rem;
}
.image-gallery img {
  width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: var(--shadow-md);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.image-gallery img:hover {
  transform: scale(1.05);
  box-shadow: var(--shadow-lg);
}

/* Card Design */
.card {
  background: linear-gradient(135deg, var(--neutral-bg), var(--color-base-muted));
  border: 1px solid var(--color-base-border);
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: var(--shadow-md);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.card:hover {
  transform: scale(1.05);
  box-shadow: var(--shadow-lg);
}
</style>

## Featured Insect Photography

<div class="image-gallery">
  <img src="/src/assets/images/Insects/NCSU_0025626_Head_View_3X.jpg" alt="Pinned Bee Specimen">
  <img src="/src/assets/images/Insects/Owen1.jpg" alt="Butterfly in Grass">
  <img src="/src/assets/images/Insects/Owen2.jpg" alt="Parasitic Wasp with Caterpillar">
  <img src="/src/assets/images/Insects/Owen3.jpg" alt="Metallic Green Tiger Beetle">
  <img src="/src/assets/images/Insects/Owen4.jpg" alt="Ant on Tree Branch">
</div>

---

## Explore Our Collection
<div class="card">
  <h2 class="text-2xl font-bold mb-4">Search Our Database</h2>
  <p>Utilize the search feature below to access detailed taxonomic records from our collection.</p>
  <autocomplete-otu class="w-full max-w-lg mx-auto my-4"/>
</div>

---

## Connect With Us
<div class="grid grid-cols-1 md:grid-cols-2 gap-8">
  
  <!-- Instagram Link Card -->
  <div class="card">
    <h2 class="text-2xl font-bold mb-4">Follow Us on Instagram</h2>
    <p>Stay up-to-date with our latest posts from the UNH Entomology Lab.</p>  
    <a href="https://www.instagram.com/unhentomologycollection" target="_blank"
       style="display: inline-block; background-color: var(--color-primary); color: var(--color-primary-content); padding: 0.5rem 1rem; border-radius: 4px; text-decoration: none; font-weight: bold;">
      Visit Instagram
    </a>
  </div>

  <!-- Get Involved Card -->
  <div class="card">
    <h2 class="text-2xl font-bold mb-4">Get Involved</h2>
    <p>Learn how you can contribute to and collaborate with the <em>{{ frontmatter.project }}</em>.</p>
    <a href="/about" class="text-blue-500 hover:underline">Learn More</a>
  </div>

</div>
