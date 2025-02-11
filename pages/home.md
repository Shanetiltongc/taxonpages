---
title: UNH Insect Database
lead: Advancing Insect Research through Taxonomic Excellence
project: UNH Insect Database
---

<!-- Header Section (Now in a Box) -->
<div class="homepage-header">
  <div class="header-box">
    <h1 class="title">{{ frontmatter.title }}</h1>
    <p class="subtitle">{{ frontmatter.lead }}</p>
  </div>
</div>

<div class="homepage-container">
  <!-- Top Section: Large Image & Info Box -->
  <div class="top-section">
    <img src="/src/assets/images/Insects/NCSU_0025626_Head_View_3X.jpg" alt="Pinned Bee Specimen" class="large-image">
    
  <!-- Main Info Box -->
  <div class="info-box">
      <h2>Explore Our Collection</h2>
      <p>Use the search feature below to access detailed taxonomic records from our collection.</p>

  <!-- Search Box (Now Filled with Accent Color) -->
  <div class="search-container">
        <autocomplete-otu class="search-bar"/>
      </div>

  <h2>Get Involved</h2>
      <p>Discover ways to contribute and collaborate with the <em>{{ frontmatter.project }}</em>.</p>

 <div class="button-container">
    <span class="cta-button">[Learn More](/pages/about.md)</span>
    <a href="https://www.instagram.com/unhentomologycollection" target="_blank" class="cta-button">Visit Instagram</a>
</div>

  </div>

  <!-- Bottom Section: Larger Four Images -->
  <div class="image-grid">
    <div class="image-box"><img src="/src/assets/images/Insects/Owen1.jpg" alt="Butterfly in grass"></div>
    <div class="image-box"><img src="/src/assets/images/Insects/Owen2.jpg" alt="Wasp carrying caterpillar"></div>
    <div class="image-box"><img src="/src/assets/images/Insects/Owen3.jpg" alt="Green beetles on rocks"></div>
    <div class="image-box"><img src="/src/assets/images/Insects/Owen4.jpg" alt="Ant on branch with larvae"></div>
  </div>
</div>

<style>
/* General Layout */
.homepage-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem;
  display: flex;
  flex-direction: column;
  align-items: center;
}

/* Header Box */
.homepage-header {
  display: flex;
  justify-content: center;
  padding: 2rem 1rem;
}

.header-box {
  width: 80%;
  padding: 1.5rem;
  background: var(--color-base-muted);
  border: 4px solid var(--color-base-border); /* Thicker border */
  border-radius: 12px;
  box-shadow: var(--shadow-md);
  text-align: center;
}

.title {
  font-size: 2.5rem;
  font-weight: bold;
}

.subtitle {
  font-size: 1.2rem;
  color: var(--color-secondary);
}

/* Top Section */
.top-section {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  gap: 2rem;
}

/* Large Image with Thicker Border */
.large-image {
  width: 50%;
  height: auto;
  border-radius: 8px;
  border: 4px solid var(--color-base-border); /* Thicker border */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Main Info Box */
.info-box {
  width: 50%;
  padding: 2rem;
  background: linear-gradient(135deg, var(--neutral-bg), var(--color-base-muted));
  border-radius: 12px;
  border: 4px solid var(--color-base-border); /* Thicker border */
  box-shadow: var(--shadow-md);
}

/* Search Box (Now Filled with Accent Color) */
.search-container {
  background: var(--color-primary-light); /* Accent color */
  border-radius: 8px;
  padding: 0.75rem;
  margin-bottom: 1rem;
}

/* Buttons: Identical Style */
.button-container {
  display: flex;
  justify-content: center;
  gap: 1rem;
  margin-top: 1rem;
}

.cta-button {
  display: inline-block;
  text-align: center;
  text-decoration: none;
  font-weight: bold;
  padding: 0.75rem 1.5rem;
  border-radius: 6px;
  border: none;
  background: var(--color-primary);
  color: var(--color-primary-content);
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: background 0.3s ease;
}

.cta-button:hover {
  background: var(--color-primary-dark);
}

/* Image Grid: Larger Images & Matching Borders */
.image-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  margin-top: 3rem;
  width: 100%;
}

.image-box {
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 12px;
  border: 4px solid var(--color-base-border); /* Thicker border */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  padding: 1rem;
  background: var(--color-base-muted);
}

.image-box img {
  width: 100%;
  height: auto;
  max-height: 400px; /* Larger images while keeping aspect ratio */
  object-fit: contain;
  border-radius: 8px;
}
</style>
